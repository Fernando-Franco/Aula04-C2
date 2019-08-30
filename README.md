# Aula04-C2

Fernando de Souza Franco
RA 1900519

<<<<<<< HEAD

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04
$ git clone https://github.com/Fernando-Franco/Aula04-C2.git
Cloning into 'Aula04-C2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04
$ cd aula04-c2

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (master)
$ git checkout -b aula04
Switched to a new branch 'aula04'

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git status
On branch aula04
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        print_01.PNG
        print_02.PNG
        print_03.PNG

no changes added to commit (use "git add" and/or "git commit -a")

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git add README.md

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git status
On branch aula04
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        print_01.PNG
        print_02.PNG
        print_03.PNG


ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git add *

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git commit -m 'Meu primeiro commit'
[aula04 f818c32] Meu primeiro commit
 4 files changed, 4 insertions(+), 1 deletion(-)
 create mode 100644 print_01.PNG
 create mode 100644 print_02.PNG
 create mode 100644 print_03.PNG

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git push --set-upstream origin aula04
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 8 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 137.72 KiB | 13.77 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
remote:
remote: Create a pull request for 'aula04' on GitHub by visiting:
remote:      https://github.com/Fernando-Franco/Aula04-C2/pull/new/aula04
remote:
To https://github.com/Fernando-Franco/Aula04-C2.git
 * [new branch]      aula04 -> aula04
Branch 'aula04' set up to track remote branch 'aula04' from 'origin'.

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git pull origin master
From https://github.com/Fernando-Franco/Aula04-C2
 * branch            master     -> FETCH_HEAD
Already up to date.

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/Fernando-Franco/Aula04-C2
   f818c32..3d90f80  aula04       -> origin/aula04
 * [new branch]      aula04_facth -> origin/aula04_facth

ferfranco@brspferfranco MINGW64 /c/Faculdade/Gestao de projetos/Aula_04/aula04-c2 (aula04)
=======
Meu primeiro commit
>>>>>>> 3d90f8006c9dd3e4bd513839aea2c2e144658bf3
