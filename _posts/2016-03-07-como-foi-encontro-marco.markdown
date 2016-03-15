---
layout: post
title:  "Como foi o Encontro em março!"
date:   2016-03-11 21:09:00
categories:
  - encontros
---

Finalmente voltamos à ativa depois de um longo período 'de férias'. Esperamos que esse encontro de hoje seja o primeiro de muito outros novos encontros.

O encontro em si foi muito bom! Tivemos várias rostos novos, diria que a maioria. O assunto principal girou em torno do tema sugerido pelo [Luciano][1] que foi [Melhoria de performance em queries][2], mas na verdade acabamos falando de melhorias em performance de uma forma geral. O formato de palestras é legal, mas acho muito mais importante o bate-papo e troca de experiência entre os participantes.

## Ruby 2.3.0 performance

Dando início ao primeiro tópico falado, listo o [post][3] do [Alexander Dymo][4] falando sobre alguns benchmarks do ruby 2.3.0 comparado com o ruby 2.2.3. O site referenciado tem outros posts bem interessantes sobre performance do ruby que valem a pena dar uma olhada.

## Virtual box / Ruby installer

Seguindo com o relato, o Jonathan perguntou se existia alguma forma melhor de usar o ruby numa máquina Windows. Ele usa numa máquina virtual [Virtual Box][5] com linux, pois ainda não domina Linux o suficiente para deixar como seu S.O. principal. Nossa recomendação foi continuar com essa configuração pois apesar de ter o recurso do [ruby installer][6], a maioria dos tutoriais, posts e artigos são feitos num ambiente UNIX, logo, é melhor ir se ambientando com Linux ou Mac. Foi comentado também sobre opções de desenvolvimento em ambientes virtuais, onde não há a necessidade de configurar nada. Não posso falar muito pois não tenho experiência no assunto, mas de toda forma, é bom para o desenvolvedor se ambientar e dominar seu ambiente de trabalho. Preparar a máquina para trabalhar, instalando o ruby, as bibliotecas necessárias e até mesmo configurando o seu editor preferido são tarefas que TODO o desenvolvedor deve fazer.

## Algumas gems para análise de performance

Voltando com o tema de performance, vimos algumas gems que fazem análise e mostram o que pode ser melhorado no código, como a [fasterer gem][7], a `fast-ruby`, [ruby-prof][8] e [stack-prof][9].

## Palestra da Eileen Uchitelle na GURUCO 2015

Essa palestra foi altamente recomendada e pode ser assistida na íntegra através do [site do Confreaks][10]. Os slides da palestra da [Eileen][11] também estão [disponíveis][12]. Vale comentar que a Eileen trabalha no [Basecamp][13] e ficou com a 'simples' tarefa de melhorar a performance do [Basecamp (produto)][14].

## Arel

O [Vagner Zampieri][16], fez uma breve apresentação do uso do [Arel][17] nas queries do [MyFinance][18]. E ficou de falar sobre "Rails Query Security", mas pelo menos compartilhou [o link][23].

## Gem Bullet

Durante o papo de performance, foi lembrado da clássica [gem Bullet][19] que ajuda a buscar queries N+1.

## RTFM

Voltando ao papo de performance, o bom e velho [Rails Guides][20] nos mostrou o que porquê devemos usar `find_each` ao invés de `all` quando for processar todos os registros de um modelo Active Record. No mesmo guides também tem uma seção destinada exclusivamente ao [upgrade de versões do Rails][21]. Muito bom!

## Análise dos testes mais lentos

Uma boa dica compartilhada foi o uso do argumento `-p`, usado no RSpec para mostrar os testes mais lentos.

## Performance do Ruby

[Leitura recomendada][22] sobre performance do ruby

## Ferramentas para análise de qualidade de código

Falamos sobre o [Code Climate][24], a versão semelhante dele, porém open source, chamada [Metric-fu][25] e uma gem que mostra possíveis [code smells][26] chamada [Reek][27].

## Livros recomendados

[Clean code][28] e [Confident ruby][29]

Até a próxima!

Abraços,
[Rafael B. Tauil][30]

[1]: https://twitter.com/lucianosousa
[2]: http://call4paperz.com/events/encontro-ruby-on-rio-marco-2016/proposals/2182
[3]: http://ruby-performance-book.com/blog/2016/02/is-ruby-2-3-faster-rails-erb-template-rendering-performance.html
[4]: https://twitter.com/alexander_dymo
[5]: https://www.virtualbox.org/
[6]: http://rubyinstaller.org/
[7]: https://github.com/DamirSvrtan/fasterer
[8]: https://github.com/ruby-prof/ruby-prof
[9]: https://github.com/tmm1/stackprof
[10]: http://confreaks.tv/videos/goruco2015-how-to-performance
[11]: https://twitter.com/eileencodes
[12]: https://speakerdeck.com/eileencodes/rubyconf-2015-how-to-performance
[13]: https://basecamp.com/about
[14]: https://basecamp.com/3/features
[15]: https://none
[16]: https://twitter.com/vagnerzampieri
[17]: https://github.com/rails/arel
[18]: http://www.myfinance.com.br/
[19]: https://github.com/flyerhzm/bullet
[20]: http://guides.rubyonrails.org/active_record_querying.html#retrieving-multiple-objects-in-batches
[21]: http://guides.rubyonrails.org/upgrading_ruby_on_rails.html
[22]: http://http://madebymarket.com/blog/dev/ruby-web-benchmark-report.html
[23]: http://rails-sqli.org/
[24]: https://codeclimate.com/
[25]: https://github.com/metricfu/metric_fu
[26]: https://en.wikipedia.org/wiki/Code_smell
[27]: https://github.com/troessner/reek
[28]: https://books.google.com.br/books/about/Clean_Code.html?id=dwSfGQAACAAJ&redir_esc=y
[29]: http://www.confidentruby.com/
[30]: https://twitter.com/tauil
