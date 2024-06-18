git log - apresenta os commits

git revert iddogit - Ele vai desfazer as alterações, nisso ele cria um novo commit, se der o git log dá pra ver, daí ele fica local e para atualizar (reverter) no remoto é necessário o git push

git reset --hard iddogit  - para apagar alterações em um commit local (as vezes voce coloca no stage area e deve ter errado, pra isso quer apagar o commit) depois é so da o git log. Obs: tem que passar o id do commit anterior ao do que foi feito (nao aquele que voce quer apagar)

git commit --amend -m "altera a mensagem do commit anterior"
depois é so da um git log

ignorando arquivos no repositório: cria um arquivo .gitignore e nele no .gitignore voce vai colocar separando por linhas:
temp/
*.css
acima vai ignorar a pasta temp e todos que são css
gitignore.io é um site que vai criar o gitignore para o projeto com aquela tecnologia.

compartilhar códigos com gist - clica no new gist onde voce consegue compartilhar trechos de código e pode ser compartilhado com outras pessoas. dai a barra de endereço é so compartilhar com o pessoal.

git log -p: basicamente voce consegue ver mais detalhes das alteraçoes usando a setinha para baixo, pra sair é so usar a tecla q

git log --graph - ao rolar voce ver o grafo de linha do tempo de um momento para outro

git show - exibe os detalhes do ultimo commit

git log --oneline: apresenta o numero do log e resumo

git diff numerodolog - Ele mostra a diferença entre dois estados, exemplo:
git diff numerolog..outronumero - de fato existe os dois pontos.

O comando git show mostra o que foi alterado em um commit enquanto o git diff mostra a diferença entre 2 pontos.

git branch nome: cria uma ramificação
git branch -m nome: muda de branch
git branch -d nome: remove a branch (voce nao pode está logado nela)
git checkout nome: muda de branch