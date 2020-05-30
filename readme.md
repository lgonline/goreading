# go 语言学习笔记


# 备忘: 提交代码的基本操作
## create a new repository on the command line

    echo "# goreading" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/lgonline/goreading.git
    git push -u origin master
                
## push an existing repository from the command line

    git remote add origin https://github.com/lgonline/goreading.git
    git push -u origin master
    …or import code from another repository
    You can initialize this repository with code from a Subversion, Mercurial, or TFS project.