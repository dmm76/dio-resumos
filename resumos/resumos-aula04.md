# DESFAZER ALTERAÇÕES
//SE DER UM GIT INIT ERRADO => REMOVER O ARQUIVO /.GIT
rm -rf .git === rf: recursividade

#FIZ ALGO ERRADO NUMA ARQUIVO OU PASTA E QUERO RETORNAR
git restore README.md

#MODIFICAR A MENSAGEM DE COMMIT
git commit --amend -m "nova mensagem"
ou
git commit --amend : vai abrir um editor de msg padrao

#GIT RESET - precisa colar o head do log do commit

git reset --soft
git reset --mixed (padrao)
git reset --hard

git add . (adiciona todos os arquivos modificados)

git log
git reflog

#remover arquivos antes de enviar para o githuv
git reset resumos/aula-02.md

git restore --staged resumos/aula-02.md

