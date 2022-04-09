git config --list
lista todas as configurações do git

git config --system
altera as configuraçõe de qualquer projeto em qualquer usuario da maquina

git config --global
altera as configurações de qualquer projeto do seu usuario da maquina

git config --local
altera as configurações apenas desse projeto

git config --global core.editor <NOME DO EDITOR>
configura um editor padrão para abrir as configurações

git config --global --edit
abre as configurações para edição

Adicionar o script abaixo para configurar atalhos do git
[alias]
	s = !git status -s
	c = !git add --all && git commit -m
	l = !git log -10 --pretty=format:'%Cblue%h%Cred%d %C(white) %ad | %Cgreen%s,%C(cyan) %cn' --date=short
