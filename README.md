# Ruby e Sass no Windows

Ruby é uma linguagem de programação interpretada multiparadigma, de tipagem dinâmica e forte, com gerenciamento de memória automático, originalmente planejada e desenvolvida no Japão em 1995, por Yukihiro "Matz" Matsumoto, para ser usada como linguagem de script. Continue lendo [Wikipedia](https://pt.wikipedia.org/wiki/Ruby_(linguagem_de_programa%C3%A7%C3%A3o)



1 – Primeiro vamos instalar o Ruby. Acesse o link para fazer o download [Download](http://rubyinstaller.org/downloads) 
image
***Cuidado: Marque a opção “Add Ruby executable to your PATH”!***

2 – vamos verificar se foi instalado corretamente. Abra o prompt / terminal e dê o comando:

ruby -v

se tudo ocorreu bem ira aparecer uma mensagem escrico algo parecido com isso:
ruby 2.2.4p230 (2015-12-16 revision 53155) [x64-mingw32]

3 – Com o Ruby instalado, iremos agora instalar o Sass. No prompt mesmo, dê o comando: 

gem install sass

Se deu algum erro, confere se o Ruby está instalado mesmo e/ou tenta instalar manualmente a gem.
	 acesse esse link [link](https://stackoverflow.com/questions/5778804/installing-ruby-gems-manuall).

4 – Se não ocorreu erros verifique o Sass de aquela conferida básica para ver se o Sass foi instalado mesmo:

sass -v

5 – vamos fazer um pequeno teste!

- Crie uma pasta para teste.
- Dentro dela crie um arquivo chamado “style.scss”.
- Nesse arquivo, coloque um código como esse:

$color-base: #000;

body { background-color: $color-base; }

6 – Vamos compilar este arquivo para o css normal.

Abra o terminal, navegue até a pasta de teste. E depois de o comando:

sass teste.scss:teste.css

7 – Da aquela conferida básica no arquivo CSS.

Se não ocoreu erros, foi gerado arquivo css na sua pasta.


Automatizando com SASS com gulp 


