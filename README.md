#latihan 1

vonix@CAHYO22 MINGW64 ~
$ mkdir lab_pemrograman

vonix@CAHYO22 MINGW64 ~
$ cd lab_pemrograman/

vonix@CAHYO22 MINGW64 ~/lab_pemrograman
$ mkdir latihan1

vonix@CAHYO22 MINGW64 ~/lab_pemrograman
$ cd latihan1/

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1
$ git init
Initialized empty Git repository in C:/Users/vonix/lab_pemrograman/latihan1/.git/

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 0

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ echo "#latihan 1" >> README.md

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ ls -l
total 1
-rw-r--r-- 1 vonix 197610 11 Oct 14 14:40 README.md

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "Cahyo"
[master (root-commit) a41d920] Cahyo
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add origin https://github.com/Hazelnuts22/Latihan_1.git

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master


vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git commit -m "Cahyo"
On branch master
nothing to commit, working tree clean

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.email "vonixgame22@gmail.com"

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git config --global user.name "Hazelnuts22"

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git remote add https://github.com/Hazelnuts22/Latihan_1.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 216 bytes | 216.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Hazelnuts22/Latihan_1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$ git clone https://github.com/Hazelnuts22/Latihan_1.git
Cloning into 'Latihan_1'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 3 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

vonix@CAHYO22 MINGW64 ~/lab_pemrograman/latihan1 (master)
$
![Screenshot (6)](https://user-images.githubusercontent.com/115677959/195798020-7db13e56-f853-485d-9c6c-93016dee93aa.png)
![Screenshot (7)](https://user-images.githubusercontent.com/115677959/195798030-6358f161-da59-4665-af4f-f3689bd34167.png)
