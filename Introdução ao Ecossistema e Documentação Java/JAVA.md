#Comandos Linux:

- Instalação -> sudo apt install curl

- Java version Manager -> curl -sL https://github.com/shyiko/jabba/raw/master/install.sh | bash && . ~/.jabba.sh
  https://github.com/shyiko/jabba

  

- utilizando o versão manager ->

jabba ls-remote  / lista as versões e implementações

jabba install openjdk@1.11  / instala passando a versão

jabba use openjdk@1.11  / troca  a versão em uso passando a versão

java -version  / confirma a versão



- Criando e executando um diretório Java

  criando  -> mkdir src

  acessar -> cd src/

  criando os outros pacotes -> mkdir com

  acessar -> cd com/

  criando os outros pacotes -> mkdir dio

  acessar -> cd dio/

  criando a classe -> vim MyFirstProgram.java

  para salvar -> :wq

  