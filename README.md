
exercise: 6

user@k25130 MINGW64 /d/Git The gym/Git-exercise (main)
$ git add unwanted.txt 

user@k25130 MINGW64 /d/Git The gym/Git-exercise (main)
$ git commit -m "umwanted commit"
[main 1e6ccd0] umwanted commit
 1 file changed, 1 insertion(+)
 create mode 100644 unwanted.txt

user@k25130 MINGW64 /d/Git The gym/Git-exercise (main)
$ git reset --hard HEAD~1
HEAD is now at ad1a19c Update README.md