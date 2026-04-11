# Ruby on Rio

Website do Ruby on Rio, destinado a divulgação de eventos e meetups para toda a comunidade do Rio de Janeiro - [rubyonrio.github.io](https://rubyonrio.github.io).

## Contribuindo

1. Faça um Fork.
2. Configure seu ambiente de desenvolvimento, como mencionado na seção (Configurando o ambiente de desenvolvimento).
3. Crie um branch (`git checkout -b my-branch`)
4. Commit suas alterações (`git commit -am 'Adicionando alguma coisa'`)
5. Envie seu branch para o repositório do github (`git push origin my-branch`)
6. Crie um novo Pull Request

## Configurando o ambiente de desenvolvimento

Verifique se a versão do ruby é a `3.4.7`:

	$ ruby -v

Senão, instale-a usando uma das opções:
 - rbenv
 - asdf (plugin ruby)
 - rvm

Execute o bundle no seu diretório para instalar as dependências:

	$ bundle

Após finalizar a instalação, execute o jekyll para ver o website rodando:

	$ bundle exec jekyll serve

Após o jekyll inicializar acesse no browser a url a seguir:

    http://localhost:4000

Para entender melhor o jekyll, [acesse aqui](https://jekyllrb.com).
