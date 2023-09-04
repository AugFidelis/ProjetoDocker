# ProjetoDocker

-Abra o prompt de comando e insira os seguintes comando:-

cd (caminho para pasta projeto-docker)

docker build -t nginx:1.0 .    (cria a imagem do nginx)


-Após isso, insira os seguintes comandos para inicializar o container:-

cd (caminho para pasta files)

docker run -d -p 9090:80 --name augfidelis-docker nginx:1.0
(cria o container com o nome augfidelis-docker com o port 9090) 


-Por último, acessar o container:-
Abra no navegador 'http://localhost:9090'
