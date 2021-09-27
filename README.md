
# git
### Um guia rápido dos comandos da ferramenta Git 
#### O guia dos comandos simples serve para sincronizar o projeto local com o projeto no GitHub
#### Alguns comandos mostram como alterar e ja fazer um commit dentro de uma Issues e também como já encerrar ela com um commit


git config --global user.name nome = adiciona o nome do usuário

git config --global user.email = adiciona o email 

git status = verifica o status do arquivo

git add nomearquivo = adiciona na stage

git add . = adiciona todas as alterações na stage

git commit -m "adiciona a mensagem" = adiciona a mensagem de commit

git commit -m " ... #2" = #2 faz o git entender que faz parte da Issues

git commit -m "... close #2" = realiza a alteração e encerra a Issues

git commit -am "mensagem" = adiciona na stage e commita ao mesmo tempo com a mensagem

git log = verifica o histórico dos commit´s

git checkout "hash-log" = mostra o arquivo nesse commit selecionado

git checkout master = volta para o estado atual do git

git clone "url" = clona o repositório remoto para o local

git pull = atualiza o repositório do github para o git local

git branch nome = cria nova branch

git branch = mostra as branch

git checkout nomedabranch = muda a branch de trabalho

git checkout -b nomedabranch = cria e ja muda para a branch criada

git merge nomedabranch = junta os commit na master e é preciso estar na master para usar o comando do merge

git log --graph = mostra o gráfico da vida 

git log --graph --online = mostra o gráfico mais resumido

git branch -d nomedabranch = exclui a branch 

git push origin nomedabranch = envia a branch para o github