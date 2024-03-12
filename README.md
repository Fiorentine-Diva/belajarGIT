Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GIT
...
C:\Windows\System32>git
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

C:\Windows\System32>cd C:/path/ke/folder/git/yang/sudah/di/clone
The system cannot find the path specified.

C:\Windows\System32>C:/path/ke/folder/git/yang/sudah/di/clone
The system cannot find the path specified.

C:\Windows\System32>cd "C:\Users\fiore\OneDrive\Documents\Pemograman Web"

C:\Users\fiore\OneDrive\Documents\Pemograman Web>git clone https://github.com/Fiorentine-Diva/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

C:\Users\fiore\OneDrive\Documents\Pemograman Web>cd belajarGIT

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-git

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout Tugas-git
Switched to branch 'Tugas-git'

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>touch Tugas-Git.txt
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-Git.txt
fatal: pathspec 'Tugas-Git.txt' did not match any files

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-Git.txt"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'fiore@FiorentDiva.(none)')

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git config --global user.email "fiorentdiva@gmail.com"

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git config --global user.name "Fiorentine Diva"

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-Git.txt"
[Tugas-git 40d2990] Menambahkan file Tugas-Git.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-Git.txt"
[Tugas-git c5bcd28] Menambahkan isi ke file Tugas-Git.txt
 1 file changed, 1 insertion(+)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-Git.txt"
On branch Tugas-git
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch Tugas-git
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch Tugas-git
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-Git
Updating 29cb267..c5bcd28
Fast-forward
 Tugas-Git.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-Git.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-Git ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 607 bytes | 202.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Fiorentine-Diva/belajarGIT.git
   29cb267..c5bcd28  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-Git ke main"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-html

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout Tugas-html
Switched to branch 'Tugas-html'

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>touch Tugas-html.txt
'touch' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 0d05e4e] Menambahkan file Tugas-html.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-html.txt"
[Tugas-html 8ee28af] Menambahkan isi ke file Tugas-html.txt
 1 file changed, 1 insertion(+)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-html.txt"
On branch Tugas-html
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch Tugas-html
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch Tugas-html
nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git chechout main
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git marge Tugas-html
git: 'marge' is not a git command. See 'git --help'.

The most similar command is
        merge

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-html
Updating c5bcd28..8ee28af
Fast-forward
 Tugas-html.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-html.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-html ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 590 bytes | 590.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   c5bcd28..8ee28af  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-css

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-css.txt"
[main c1ce7c8] Menambahkan file Tugas-css.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-css.txt"
[main 5ec6b91] Menambahkan isi ke file Tugas-css.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-css.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-css.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-css
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-css ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 553 bytes | 276.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   8ee28af..5ec6b91  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-js

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-js.txt"
[main bb53015] Menambahkan file Tugas-js.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-ja.txt"
[main 8f28d1f] Menambahkan isi ke file Tugas-ja.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-js.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-js.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-js.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 554 bytes | 277.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   5ec6b91..8f28d1f  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-Git
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-js
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-js ke main"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-midProject

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-midProject.txt"
[main 983a168] Menambahkan file Tugas-midProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-midProject.txt"
[main cf4d838] Menambahkan isi ke file Tugas-midProject.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-midProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-midProject.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-midProject
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-midProject ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 582 bytes | 582.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   8f28d1f..cf4d838  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-php

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-php.txt"
[main 48120fd] Menambahkan file Tugas-php.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-php.txt"
[main d59d747] Menambahkan isi ke file Tugas-php.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-php.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-php.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-php
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-php ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 555 bytes | 555.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   cf4d838..d59d747  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git branch Tugas-finalProject

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>echo. > Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan file Tugas-finalProject.txt"
[main 03d42d2] Menambahkan file Tugas-finalProject.txt
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan isi ke file Tugas-finalProject.txt"
[main 0301629] Menambahkan isi ke file Tugas-finalProject.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git add Tugas-finalProject.txt

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-finalProject.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Menambahkan perubahan pada file Tugas-finalProject.txt"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Commit kosong: Tidak ada perubahan baru"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git merge Tugas-finalProject
Already up to date.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git commit -m "Merge cabang Tugas-finalProject ke main"
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 619 bytes | 619.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/Fiorentine-Diva/belajarGIT.git
   d59d747..0301629  main -> main

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git checkout main
Already on 'main'
Your branch is up to date with 'origin/main'.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>git push origin main
Everything up-to-date

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad README.md

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>- `git add`: Menambahkan perubahan dari working directory ke staging area.
'-' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>notepad README.md

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>- `git add`: Menambahkan perubahan dari working directory ke staging area.
'-' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>dir
 Volume in drive C is Windows-SSD
 Volume Serial Number is A0C7-9113

 Directory of C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT

03/10/2024  11:33 PM    <DIR>          .
03/10/2024  07:40 PM    <DIR>          ..
03/10/2024  07:40 PM               163 README.md
03/10/2024  11:05 PM                11 Tugas-css.txt
03/10/2024  11:36 PM                38 Tugas-finalProject.txt
03/10/2024  10:26 PM                31 Tugas-Git.txt
03/10/2024  10:50 PM                31 Tugas-html.txt
03/10/2024  11:14 PM                29 Tugas-js.txt
03/10/2024  11:23 PM                37 Tugas-midProject.txt
03/10/2024  11:30 PM                30 Tugas-php.txt
               8 File(s)            370 bytes
               2 Dir(s)  350,775,709,696 bytes free

C:\Users\fiore\OneDrive\Documents\Pemograman Web\belajarGIT>
