aulaQuinta
Repositorio p/ aula de quinta

Configurar Proxy:
Se o seu RA é "12345" e sua senha é "OtimoAluno" o seu comando será: git config --global http.proxy http://12345:OtimoAluno@186.251.39.91:3128 git config --global https.proxy https://12345:OtimoAluno@186.251.39.91:3128

Configurar os seus dados no git
git config --global user.email "you@example.com" git config --global user.name "Your Name"
Para começar a versionar
#Inicializa o repositorio
	git init

#Rastreia os arquivos
	git status

#adiciona os arquivos com mudanças para serem 'commitados'
	git add .

#Faz um commit e insere na branch que eu estou
	git commit -m "comento o que eu mudei"

#Adicionar o repositorio
	git remote add origin https://github.com/Rafaelcerq28/aulaQuinta.git

#Grava no git
	git push -u origin master
