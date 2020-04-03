# aulaQuinta
Repositorio p/ aula de quinta

<h4>Configurar Proxy:</h4>

 Se o seu RA é "12345" e sua senha é "OtimoAluno" o seu comando será:
  	git config --global http.proxy http://12345:OtimoAluno@186.251.39.91:3128
  	git config --global https.proxy https://12345:OtimoAluno@186.251.39.91:3128

	
<h4>Configurar os seus dados no git</h4>	
	git config --global user.email "you@example.com"
	git config --global user.name "Your Name"

<h4>Para começar a versionar</h4>

	#Inicializa o repositorio
		git init

	#Rastraia os arquivos
		git status

	#adiciona os arquivos com mudanças para serem 'commitados'
		git add .
	
	#Faz um commit e insere na branch que eu estou
		git commit -m "comento o que eu mudei"
	
	#Adicionar o repositorio
		git remote add origin https://github.com/Rafaelcerq28/aulaQuinta.git

	#Grava no git
		git push -u origin master
