Git_usage
=========

Git command usage


###Create:
    touch README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/yestab123/test.git
    git push -u origin master


###Update:
    git remote add origin https://github.com/yestab123/test.git
    git pull -u origin master
    git add  XXXXXX
    git commit -m "XXXXXX"
    git push -u origin master
    (若git push 报403，修改.git/config中url，在github.com前面加上 username@，即 https://yestab123@github.com/XXXXX/XXXX.git)

###Delete
    git rm XXXX
    git commit -m "XXXXXXX"
    git push -u origin master
    
###Release
    git tag v1.0.0
    git push -u origin v1.0.0
