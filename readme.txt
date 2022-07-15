1 - criei um usuário: git config --global user.name "Frederico" [ENTER]

2 - configurei o e-mail do usuário: git config --global user.email "frederico.dos.santos@gmail.com" [ENTER]

3 - configurei o editor principal do git: git config --global core.editor "brackets"

======================================================================================================
comandos interessantes a se usar:

git config user.name  <-- retorna o usuário

git config email  <-- retorna email do usuário

git config --list  <-- retorna toda a configuração


================================================================================================================

git init <-- inicializa o repositório
Initialized empty Git repository in C:/xampp2/htdocs/git-course/.git/   <---retorno
=============================================================================================
git status 

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        readme.txt

nothing added to commit but untracked files present (use "git add" to track)

================================================================================================================

digita [git add readme.txt] outra vez e então
 
[git status] traveis

On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.txt

=============================================================================================
com o commit criei uma imagem do meu diretório:

 git commit -m "Add readme.txt"
[master (root-commit) 70e4b77] Add readme.txt
 1 file changed, 50 insertions(+)
 create mode 100644 readme.txt

=============================================================================================
com um git status dá pra ver que não a mais nada a ser feito por enquanto pq acabou de ser tirada uma foto do atual estado

git status
On branch master
nothing to commit, working tree clean

=============================================================================================

modifiquei o arquivo novamente
=============================================================================================
 git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

no changes added to commit (use "git add" and/or "git commit -a")


===================================================================================
git diff   <---- mostra as diferenças