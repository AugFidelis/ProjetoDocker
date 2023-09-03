# ProjetoDocker

-Abra o prompt de comando e insira o seguinte comando:-

docker build -t nginx:1.0 .    (cria a imagem do nginx)


-Após isso, insira o seguinte comando para inicializar o container:-

docker run -d -p 9090:80 --name augfidelis-docker nginx:1.0
(cria o container com o nome augfidelis-docker com o port 9090) 


-Por último, acessar o container:-
Abra no navegador 'http://ip-do-host:9090'
