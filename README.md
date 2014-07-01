# Ruby on Rio

Website do Ruby on Rio - [rubyonrio.github.io](http://rubyonrio.github.io)

## Contribuindo

1. Faça um Fork.
2. Configure seu ambiente de desenvolvimento, como mencionado na seção(Configurando o ambiente de desenvolvimento).
4. Crie um branch (`git checkout -b my-branch`)
5. Commit suas alterações (`git commit -am 'Adicionando alguma coisa'`)
6. Envie seu branch para o repositório do github (`git push origin my-branch`)
7. Crie um novo Pull Request

## Configurando o ambiente de desenvolvimento


Execute o bundle no seu diretório para instalar as dependências:

	$ bundle

Após finalizar a instalação, execute o jekyll para ver o website rodando:

	$ jekyll serve


Após o jekyll inicializar acesse no browser a url a seguir:

    http:://localhost:4000

O arquivo css a ser alterado é o `sass/main.scss` e para as alterações serem compiladas, basta executar:

	$ compass compile


Para entender melhor o jekyll, [acesse aqui](http://jekyllrb.com).
