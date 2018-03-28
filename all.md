#Aula 10
git log
commit (identificação)
Author
Date:

	-m mensagens


git log --decorate

git log --author="nome" (pode escrever só parte do nome)

git shortlog (mostra em ordem alfabética quais foram os autores, quantos commits fizeram e quais eles foram)

git shotlog -sn (quantidade de commits e nome)

git log --graph (mostra em forma gráfica)

git show [código da hash]


#Aula 11
git diff
Mostra modificações nos arquivos antes de commitar
Bom para dar uma última olhada nas modificações que foram feitas


git diff --name-only
Mostra somente uma lista com os nomes dos arquivos que foram modificados


git commit -am "Aula 11"
Quando o arquivos já foi commitado antes, pode-se usar a linha de comando acima para commitá-lo.