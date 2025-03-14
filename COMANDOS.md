##COMANDOS GCLOUD
gcloud -v #versão do gcloud
gcloud auth login #loga no gcloud
gcloud init #inicializa o gcloud

##GIT
git -v #versão do git
git -h #ajuda do git
git clone [link] #clona um repositório
git status #status do repositório
git add . #adiciona todos os arquivos
git commit -m "mensagem" #commita os arquivos
git push #envia os arquivos para o repositório
git pull #atualiza os arquivos do repositório

##MAVEN
mvn -version #versão do maven
mvn clean #limpa o projeto
mvn test #roda os testes do projeto (testes unitários)
mvn verify #verifica o projeto
mvn site #gera o site do projeto
mvn compile #compila o projeto
mvn package #empacota o projeto
mvn install #instala o projeto
mvn appengine:deploy #faz o deploy do projeto
mvn appengine:run #roda o projeto
#COMANDO USADO PARA CORRER O PROJETO LOCALMENTE
mvn package appengine:run #empacota e roda o projeto