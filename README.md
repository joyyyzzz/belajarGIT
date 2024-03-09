Daftar tugas / branch
  1. Tugas-git
  2. Tugas-html
  3. Tugas-css
  4. Tugas-js
  5. Tugas-midProject
  6. Tugas-php
  7. Tugas-finalProject

Daftar perintah Git

jzzzyyyy@User MINGW64 ~
$ cd "C:\Users\User\Joy\Kuliah\pemroweb"

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb
$ git clone https://github.com/joyyyzzz/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb
$ cd belajarGIT

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ ls
README.md

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt"
[Tugas-git 1875f07] Menambahkan Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-git
Updating f0ee4d4..1875f07
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 299 bytes | 299.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/joyyyzzz/belajarGIT.git
   f0ee4d4..1875f07  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Html.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Html.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt"
[Tugas-html da88760] Menambahkan Tugas-Html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-html
Updating 1875f07..da88760
Fast-forward
 Tugas-Html.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Html.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 323 bytes | 323.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/joyyyzzz/belajarGIT.git
   1875f07..da88760  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ touch Tugas-Css.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Css.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Css.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Css.txt"
[Tugas-css 768f291] Menambahkan Tugas-Css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-css
Updating da88760..768f291
Fast-forward
 Tugas-Css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Css.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 357 bytes | 357.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/joyyyzzz/belajarGIT.git
   da88760..768f291  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ touch Tugas-Js.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Js.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Js.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-Js.txt"
[Tugas-js 77044d6] Menambahkan Tugas-Js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-js
Updating 768f291..77044d6
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 310 bytes | 310.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joyyyzzz/belajarGIT.git
   768f291..77044d6  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ touch Tugas-MidProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-MidProject.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-MidProject.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-MidProject.txt"
[Tugas-midProject 6d94bb1] Menambahkan Tugas-MidProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-js
Already up to date.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-midProject
Updating 77044d6..6d94bb1
Fast-forward
 Tugas-MidProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-MidProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 305 bytes | 305.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joyyyzzz/belajarGIT.git
   77044d6..6d94bb1  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout Tugas-php
error: pathspec 'Tugas-php' did not match any file(s) known to git

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ touch Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Php.txt

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Php.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-Php.txt"
[Tugas-php 713b334] Menambahkan Tugas-Php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-php
Updating 6d94bb1..713b334
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 292 bytes | 292.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/joyyyzzz/belajarGIT.git
   6d94bb1..713b334  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-FinalProject

nothing added to commit but untracked files present (use "git add" to track)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-FinalProject


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt
fatal: pathspec 'Tugas-FinalProject.txt' did not match any files

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ touch Tugas-FinalProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-FinalProject

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-FinalProject

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-FinalProject.txt


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-FinalProject
        new file:   Tugas-FinalProject.txt

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    Tugas-FinalProject


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan Tugas-FinalProject.txt"
[Tugas-finalProject 260eee3] Menambahkan Tugas-FinalProject.txt
 2 files changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject
 create mode 100644 Tugas-FinalProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-php
Already up to date.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 713b334..260eee3
Fast-forward
 Tugas-FinalProject     | 0
 Tugas-FinalProject.txt | 1 +
 2 files changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject
 create mode 100644 Tugas-FinalProject.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout Tugas-finalproject
Switched to branch 'Tugas-finalproject'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalproject)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git branch
  Tugas-css
* Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
  main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ ls
README.md           Tugas-FinalProject.txt  Tugas-Js.txt
Tugas-Css.txt       Tugas-Git.txt           Tugas-MidProject.txt
Tugas-FinalProject  Tugas-Html.txt          Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git reset Tugas-FinalProject
fatal: ambiguous argument 'Tugas-FinalProject': both revision and filename
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ ^C

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git reset -- Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ ls
README.md           Tugas-FinalProject.txt  Tugas-Js.txt
Tugas-Css.txt       Tugas-Git.txt           Tugas-MidProject.txt
Tugas-FinalProject  Tugas-Html.txt          Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git delete Tugas-FinalProject
git: 'delete' is not a git command. See 'git --help'.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git rm Tugas-FinalProject
rm 'Tugas-FinalProject'

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ ls
README.md      Tugas-FinalProject.txt  Tugas-Html.txt  Tugas-MidProject.txt
Tugas-Css.txt  Tugas-Git.txt           Tugas-Js.txt    Tugas-Php.txt

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
D       Tugas-FinalProject
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'
D       Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        deleted:    Tugas-FinalProject


jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git commit -m "Menghapus error"
[Tugas-finalProject 318e569] Menghapus error
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git merge Tugas-finalProject
Updating 260eee3..318e569
Fast-forward
 Tugas-FinalProject | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 Tugas-FinalProject

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$ git push origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 481 bytes | 481.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/joyyyzzz/belajarGIT.git
   713b334..318e569  main -> main

jzzzyyyy@User MINGW64 ~/Joy/Kuliah/pemroweb/belajarGIT (main)
$
