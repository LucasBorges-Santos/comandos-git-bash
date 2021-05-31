# comandos-git-bash
comandos para subir projeto no github.

Configurando usuario:

	git config --global user.name "username"
	git config --global user.email "email"


Subindo projetos:

	git init
	git status
	git add .
	git status
	git commit -m "arquivos"
	git remote add origin <link clone>
	git push origin master
	

clonando projetos:

	git clone <link do projeto>

Se der um erro de origem com a mensagem "is this a git repository?":
	https://stackoverflow.com/questions/43049278/fatal-git-info-refs-not-valid-is-this-a-git-repository
