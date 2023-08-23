
# Resumos Git e GitHub

Comandos iniciais para github.

Editor de .MD  (readme.so)

## 📚 Documentação
https://git-scm.com/book/en/v2

(*)comandos git
1 - git init
2 - git status deve estar vermelho
3 - git add nome do arquivo ou git add .
4 - git status muda para verde
5 - git commit - a -m"comentario"
6 - git status  -  finalizacao do processo.
7 - agora e copiar os links do github


## 😉 Atalhos

| Atalho | Descrição |
|--------|-----------|
|(W) + (.) | Insere Emogions |


## comandos GIT
| Atalho | Descrição |
|--------|-----------|
| git init | inicializa repositório |
| git clone | clona um repositório |
git status • verifica se alguma mudança foi feita no brach atual
git add • adiciona arquivos, para area de preparação.
git add . • com o (.) adiciona toda a pasta, para area de preparação.
git commit -a -m "inserir comentario" • Enviar area de preparação para Commit.
git reset • volta o codigo a algum ponto especifico
git checkout • descarta mudanças em algum arquivo especifico
git brach • listagem de branches
git checkout • altera o branch
git pull • recebe atualizações do repo remoto
git push • envia atualizações para o repo remoto
git fetch • recebe branches remotos que nao estão mapeados
git log • Apresenta ultimo commit
q • sair do (git log)
git remote show origin • saber qual repositorio estamos

## DESFAZER 
| Atalho | Descrição |
|--------|-----------|
git restore <arquivo> • restaura arquivo editado com o status do Git.
git commit --amend -m"comentario" • Substitui comentario do Commit.
git reset --soft <rest do commit que vai retornar> • reseta commit anteriores.
git reset --mixed <rest do commit que vai retornar> • adciona arquivos do commit anteriar a area de preparação.
git reset --hard <rest do commit que vai retornar> • apaga tudo até o commit informado.
git reset <Arquivo> • Remove arquivo da area de preparação.

## Branche (Ambiente de Desenvolvimento)
| Atalho | Descrição |
|--------|-----------|
| git checkout -b <NomeBranch> | Cria nova Branch |
| git checkout <NomeBranch> | Troca de Branch |
| git branch -v | Lista Ultimo Commit de cada Branch |
| git branch -v | Ultimo commit da branch |
| git merge <NomeBranch> | mescla as branch |
| git branch | lista as branch |
| git branch -d <NomeBranch> | Apaga a Branch |
| *************** | *************** |
| git fetch <origin> <main> | baixa brach e não sobrepoe do local |
| git diff <main> <originn/main> | amonstra diferenças entre as branch |
| git merge <origin>/<main> | junta as duas branch |
| git clone <endereçoRepositorio> --branch <nomeBranch> --single-b | clona apenas 1 branch |
| git stash | volta com arquivos deletados |
| git stash list | Lista modificações que voltou |
| git checkout -b teste-2 | cria nova branch e vai para ela |
| git stash apply | aplica a modificação arquivada |






clear • limpa tela
. • abre o editor online

touch README.mbd • criar arquivo de texto


