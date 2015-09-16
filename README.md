# tutorial_git
oficina do ftsl


programas: git gitk

comandos linux:
cal 1752	//calendario
touch		//cria arquivos vazios

comandos:

git init
git config --global user.name tomas
git config --global user.email tomas.abril@gmail.com
// global na maquina // sem global no projeto
configuracoes ficam em .gitconfig

git help
git help init
git status
nano texto
git add texto
git add .	//adiciona tudo

git commit -m 'commit inicial'
git log
touch texto3 texto4	//do linux
git checkout -- texto	//volta modificacao no arquivo desde o ultimo commit
rm --cached texto2	//tira do indice
git add -i		//opcoes _interativas_ do add

git reset HEAD-1 --hard	//volta um comit atras
git reflog		//mostra o que aconteceu/ultimos commits feitos e desfeitos
git merge b4a679a	// recoloca um commit apagado / codigo do commit que vai voltar
git reset HEAD-1 --soft	//desfaz o commit mas nao as alteraçoes dos arquivos

git commit -m 'mudando um commit' --amend	//modifica um commit ja feito
git diff texto		// mostra o diff desde o ultimo commit
git blame texto		//mostra quem fez as mudancas
nano .gitignore		//escrever dentro dele os arquivos a serem ignorados no projeto/ precisa ser comitado ao projeto
git commit -a -m 'mensagem'	//adiciona arquivos e faz commit

>>quarta dimenção do git
git stash		//guarda modificacoes em um lugar separado
git stash list		//lista os stashes
git stash apply		//stash@{0}//tras de volta um stash
git stash clear		//apaga os stash

>>branches  <<-
git checkout -b nomedobranch	//cria e muda para a branch
git branch		//lista as branches
git checkout master	// muda de branch
git merge nomedobranch	// junta a branch com a master
git rebase master	// faz rebase da branch atual com a master
https://www.atlassian.com/git/tutorials/merging-vs-rebasing/conceptual-overview














