EXEMPLO de ERRO

tentar salvar num diretorio vazio - o git vai dar erro
POR CONVENSÃO - OS DEVS UTILIZAM UM AQUIVO .gitkeep

//adicionando uma pasta vasia
touch aulas/.gitkeep

mkdir resumos
touch resumos/resumo-aula01.md

//se quiser ignorar a pasta resumos ao fazer o upload
echo resumos/ > .gitignore

