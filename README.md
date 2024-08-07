Exercicio01
 git status On branch main Your branch is up to date with 'origin/main'.
Untracked files: (use "git add ..." to include in what will be committed) arquivo.txt

nothing added to commit but untracked files present (use "git add" to track)
git add . warning: LF will be replaced by CRLF in arquivo.txt. The file will have its original line endings in your working directory
 git status On branch main Your branch is up to date with 'origin/main'.
  git commit -m "git add example - arquivo.txt" [main 790ea9e] git add example - arquivo.txt 1 file changed, 1 insertion(+) create mode 100644 arquivo.txt
  git diff arquivo.txt warning: LF will be replaced by CRLF in arquivo.txt. The file will have its original line endings in your working directory diff --git a/arquivo.txt b/arquivo.txt index 8a0f05e..9e22bcb 100644 --- a/arquivo.txt +++ b/arquivo.txt @@ -1 +1 @@ -01 +02
   git add arquivo.txt warning: LF will be replaced by CRLF in arquivo.txt. The file will have its original line endings in your working directory
   git status On branch main Your branch is ahead of 'origin/main' by 1 commit. (use "git push" to publish your local commits)
   git diff --staged arquivo.txt diff --git a/arquivo.txt b/arquivo.txt index 8a0f05e..9e22bcb 100644 --- a/arquivo.txt +++ b/arquivo.txt @@ -1 +1 @@ -01 +02
   git diff arquivo.txt warning: LF will be replaced by CRLF in arquivo.txt. The file will have its original line endings in your working directory diff --git a/arquivo.txt b/arquivo.txt index 9e22bcb..75016ea 100644 --- a/arquivo.txt +++ b/arquivo.txt @@ -1 +1 @@ -02 +03
   git restore --staged arquivo.txt
   git status On branch main Your branch is ahead of 'origin/main' by 1 commit. (use "git push" to publish your local commits)
   git commit -m "Adds restored arquivo.txt file from staging" On branch main Your branch is ahead of 'origin/main' by 1 commit. (use "git push" to publish your local commits)
   git log --oneline 790ea9e (HEAD -> main) git add example - arquivo.txt 377e2ab (origin/main, origin/HEAD) Initial commit
   git status On branch main Your branch is ahead of 'origin/main' by 1 commit. (use "git push" to publish your local commits)
   git add .gitignore warning: LF will be replaced by CRLF in .gitignore. The file will have its original line endings in your working directory
   git commit -m "Adds .gitignore to ignore .txt files" [main cacbc25] Adds .gitignore to ignore .txt files 1 file changed, 1 insertion(+) create mode 100644 .gitignore
   git status On branch main Your branch is ahead of 'origin/main' by 2 commits. (use "git push" to publish your local commits)
   no changes added to commit (use "git add" and/or "git commit -a")
   
