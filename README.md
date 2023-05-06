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
## switch ke branch 
 git checkout test
## perintah untuk membuat branch dan pilih ke branch tersebut
 git checkout -b testb
## perintah untuk merge
 git merge master
# untuk mengedit commentar commit 
git commit --amend
 -kemudian untuk push ke git repository nya
git push --force example-branch
# cara clone semua branch
	git clone git://example.com/myproject
	cd myproject
	git branch
$ git branch -a
* master
  remotes/origin/HEAD
  remotes/origin/master
  remotes/origin/v1.0-stable
  remotes/origin/experimental
If you just want to take a quick peek at an upstream branch, you can check it out directly
$ git checkout origin/experimental
$ git checkout -b experimental origin/experimental
and you will see
Branch experimental set up to track remote branch experimental from origin.
Switched to a new branch 'experimental'
  git branch
  experimental
  master
# Cara setting single repository
git config user.email "your_email@example.com"
git config user.email
# Untuk menghapus branch
  git push origin --delete <branch_name>
  git branch -d <branch_name>

# Delete Local Branch
 git branch -d branch_name

# How to create tag
```bash
git tag v1.0.1
```
# How to delete tag
```bash
git tag - v1.0.1
```

