---
layout: post
title:  "Como foi o Encontro em abril!"
date:   2016-04-27 11:00:00
categories:
  - encontros
---

Demorei para fazer esse post, mas antes tarde do que nunca!

O encontro de Abril aconteceu no dia 11 e novamente tivemos um bom quórum de participantes. Seguimos o mesmo modelo do encontro anterior onde cada um fala um pouco sobre o assunto que desejar e um assunto vai emendando no outro. Fica como se fosse um bate-papo mas com bastante conteúdo.

Iniciamos o encontro comigo mostrando [um projeto open source][2] que tenho trabalhado com outros desenvolvedores. Trata-se de um jogo de tabuleiro online baseado no [jogo de tabuleiro][3] do [Game of Thrones][4]. A ideia era basicamente contar como é importante contribuir para projetos open source e como isso além de te entreter te ajuda a melhorar o seu networking e suas seu conhecimento técnico. Também comentei sobre outro projeto open source que dedico parte do meu tempo, o [Call4Paperz][5]. A partir desse tema iniciamos uma conversa sobre [Github][6] Vs [Bitbucket][7]. Sabemos que cada um tem seus pontos bons e ruins, mas se vai trabalhar em projetos open source, o Github de fato é a melhor opção, principalmente por ter a maioria dos projetos open source hospedados lá e a comunidade está muito mais ativa lá.

Dando continuidade ao bate-papo falamos sobre [Jekyll][8] e que esse site do RubyOnRio é feito usando essa tecnologia. Falamos como é possível fazer bastante coisa usando apenas Jekyll e alguns plug-ins dele. As possibilidades são infinitas, desde documentação de projetos e APIs até sites pessoais. Ele é tão simples que lembramos do bom e velho [Sinatra][9]. Comentei que acho o sinatra fantástico, mas que dependendo da necessidade do projeto, não faz muito sentido usa-lo em dentrimento ao [Rails][10]. O Sinatra até tem algumas versões mais elaboradas como o [Padrino][11], mas que sinceramente e particularmente não vejo muito sentido em usar. O Rails é um framework fantástico e cumpre com todos os requisitos que o Padrino oferece. Posso estar desmerecendo um pouco o projeto, mas o pouco que vi do Padrino não me convenceu a usá-lo ao invés do Rails.

Em seguida o [André Fonseca][12] iniciou sua contribuição para o encontro. Ele começou falando com um tema bastante comum no mercado de trabalho atual: "Como convencer o seu time ou empresa a mudar de tecnologia?". Esse assunto gerou um papo bom e contribuição de bastante pessoas. Basicamente a conclusão que chegamos na hora foi de que é sempre importante optar por uma tecnologia mais adequada para a necessidade do projeto porém é mais importante ainda entender a realidade do time, quais os recursos que tem no momento e chegar num meio termo. Em outras palavras, se o seu time sabe mais sobre Ruby do que Node e a necessidade do projeto aceita ambas as tecnologias como solução, opte pela que será mais produtiva pela equipe, no caso do exemplo, Ruby.

Ainda nesse tema, André mostrou como um simples script em Python o ajudou a automatizar e acelerar uma tarefas que era feita manualmente na empresa. As vezes um simples script podm ajudar bastante na automatização de um processo, podendo ter até binários para esses scripts. No mundo Ruby por exemplo você pode fazer um script e utilizar o [Thor][13]. Essa gem é a responsável por gerar qualquer script Ruby em arquivos binários, assim como é feito com o Bundler, Vagrant, Rails e muitos outros.

Falando de Rails e outras tecnologias o papo começou a girar em torno de performance e como é possível sim ter projetos super performaticos com Ruby on Rails. Um exemplo citado por André foi de que é muito comum ver desenvolvedores cometendo erros basicos de configuração como ajustar corretamente o [pool de conevões do Rails com o banco de dados][14]. O Luciano também citou que muitos também esquecem de [limpar os dados][15] escritos no [Redis][16] pelo [Sidekiq][17].

Algumas barreiras também foram citadas como problemas para mudar a tecnologia usada em algumas empresas, como por exemplo não ser possível rodar o Ruby no servidor da empresa. Nesse caso o André comentou sobre o [Warbler][18], empacotador bit code para Java. Nesse caso é necessário ter o [JRuby][23] para gerar o bit code.

Performance é um assunto sempre polêmico, sendo assim André propôs a seguinte reflexão: "Não adianta falar que não é performatico. O que é performance?". Essa reflexão sugere a todos nós pensarmos bem sobre o tema e o que realmente é necessário para solucionar o problema. Muitas vezes um simples cache ou ajuste fino nas configurações do seu servidor podem resolver o problema. Nesse momento foi citado o nome do nosso saudoso e sumido colega do RubyOnRio [Rafael Martins a.k.a. Cabra][19]. Cabra tem uma vasta experiência em performance com Ruby e outras tecnologias também. Experiência obtida através dos projetos por onde está e passou na [Globo.com][20]. Outra grande referência sobre performance e que também está na Globo.com é o [Vinicius Pacheco][21] que já palestrou em alguns eventos e também é colega nosso no RubyOnRio. Ambos trabalharam com o André na Globo.com.

Não lembro ao certo agora, mas pelas minhas anotações vi que também foi falado que é bem performatico utilizar [Puma][22] com [JRuby][23].

E pra não perder a piada algum engraçadinho lembrou da [maior aplicação monolítica em Rails][24] e que é bem performatico ([tem video também][27]). Trata-se de um site de [Receitas][28] e que "basicamente" a solução para escalar a aplicação foi subir um monte de servidor nos horarios de pico! Foi uma descrição simplória minha. Assistam o video que vale a pena!

Fechando sua participação, André comentou sobre um post que viu do Fábio Akita sobre [o fim do ruby][26] e recomendou ~~~um livro que ainda não consegui pegar o nome correto, mas atualizarei o post assim que conseguir~~~ [essa palestra do Joshua Kerievsky][29].

No final do encontro, conversando sobre ideias e pedindo sugestões de temas para os próximos encontros, comentei sobre uma ideia maluca que me ocorreu referente ao tema de performance. Basicamente seria uma "luta" entre aplicações. Ambas deveria mandar requests e responder aos requests o mais rápido possível e esses requests iriam aumentando até que uma dessas aplicações não aguentasse mais responder e perderia o desafio. É claro que tem muitas lacunas sobre como fazer isso acontecer e como julgar. Talvez teria que ter um outra aplicação escutando os dois, não sei. Só uma ideia que me ocorreu na hora. Também sugeri um uso alternativo no Call4paperz de modo a nos ajudar para os próximos enconros. Ao invés de inscrever as propostas quer falar, seria a inscrição de quais temas gostaria de ouvir.

Até a próxima!

Abraços,

[Rafael B. Tauil][1]

[1]: https://twitter.com/tauil
[2]: https://github.com/got-board-team
[3]: https://www.galapagosjogos.com.br/jogos/a-guerra-dos-tronos-board-game
[4]: https://pt.wikipedia.org/wiki/Game_of_Thrones
[5]: http://call4paperz.com/
[6]: https://github.com/
[7]: https://bitbucket.org/
[8]: https://github.com/jekyll/jekyll
[9]: https://github.com/sinatra/sinatra
[10]: https://github.com/rails/rails
[11]: https://github.com/padrino/padrino-framework
[12]: https://twitter.com/aoqfonseca
[13]: https://github.com/erikhuda/thor
[14]: http://stackoverflow.com/questions/15086880/correct-setting-of-database-connection-pool-database-yml-for-single-threaded-rai
[15]: https://coderwall.com/p/gefcig/flush-sidekiq-s-redis-db
[16]: http://redis.io/
[17]: https://github.com/mperham/sidekiq
[18]: https://github.com/jruby/warbler
[19]: https://twitter.com/rafael_mws
[20]: http://globo.com
[21]: https://twitter.com/ViniciusPach
[22]: http://puma.io/
[23]: http://jruby.org/
[24]: https://speakerdeck.com/a_matsuda/the-recipe-for-the-worlds-largest-rails-monolith
[25]: livro andre
[26]: https://www.quora.com/What-happened-to-the-Ruby-community-Where-did-everybody-go/answer/Fabio-Akita?share=c45443c0
[27]: https://www.youtube.com/watch?v=naTRzjHaIhE
[28]: https://cookpad.com/br?via=jp
[29]: http://www.infoq.com/interviews/anzen
