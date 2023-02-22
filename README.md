# zapis git push
Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ winpty gh.exe auth login
? You're already logged into github.com. Do you want to re-authenticate? No
? You're already logged into github.com. Do you want to re-authenticate? (y/N)
Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ gh auth login
? What account do you want to log into?  [Use arrows to move, type to filter]
> GitHub.com
  GitHub Enterprise Server
could not prompt: Niepoprawna funkcja.

Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ git config --global user.name pstarzecc

Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ git config -- global user.email pawel.starzec@zst.kolbuszowa.pl
fatal: not in a git directory

Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ git config -- global user.email pawel.starzec@zst.kolbuszowa.pl
fatal: not in a git directory

Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ pwd
/c/Users/Pawel

Pawel@DESKTOP-5RJ21C4 MINGW64 ~
$ cd ~/untitled4

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ ls
CMakeLists.txt  cmake-build-debug/  main.cpp

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ echo "# zadanie" >> README.md

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ git init
Reinitialized existing Git repository in C:/Users/Pawel/untitled4/.git/

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ git commit -m "first commit"
[master (root-commit) 446c76e] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (master)
$ git branch -M main

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (main)
$ git remote add origin https://github.com/pstarzecc/zadanie.git
error: remote origin already exists.

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 226 bytes | 226.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/pstarzecc/zadanie.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Pawel@DESKTOP-5RJ21C4 MINGW64 ~/untitled4 (main)
$ 

