# BELAJAR GIT
## cara install git di Linux ubuntu
    sudo apt-get install git
## cara inisialisasi repository git
    git init
## cara menambahkan file ke staging index
    git add . atau juga bisa menggunakan git add --al
## update repository 
    git commit -m "initial commit"
    -m : untuk menambahkan message
    git add . (dot) untuk memperoses semual file
## cara untuk unstaging index
    git reset HEAD : HEAD adalah mereset ke commit terakhir undo
## cara reset soft reset dengan file detail
    git reset HEAD File_A
## untuk melihat status
    git status
## untuk melihat log
    git log
## membatalkan commit
    git commit --amend
## log dengan online
    git log --online
## untuk melihat perbedaan file yang belum di masukan ke staging index
    git diff File_A
## untuk menambahkan branch
 :example : git branch test_branch
 ### switch ke branch 
 git checkout test
 ### perintah untuk membuat branch dan pilih ke branch tersebut
 git checkout -b testb
 ### perintah untuk merge
 git merge master

