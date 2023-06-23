# BELAJAR GIT
## Cara install git di Linux ubuntu
```bash
sudo apt-get install git
```
## Cara inisialisasi repository git
```bash
git init
```
## Cara menambahkan file ke staging index
```bash
git add .
```
Atau
```bash
 git add --all
```
## Update repository 
```bash
git add .
```
```bash
git commit -m "initial commit"
```
Note:
- -m : untuk menambahkan message
- git add . (dot) untuk memperoses semual file
## Cara untuk unstaging index
```bash
git reset HEAD
```
Note : 
- HEAD adalah mereset ke commit terakhir undo

## Cara reset soft reset dengan file detail
```bash
git reset HEAD File_A
```
## Cara untuk melihat status
```bash 
git status
```
## Cara untuk melihat log
```bash
git log
```
```bash
git bash --oneline
```
```bash
git bash --graph
```
## Cara membatalkan commit
```bash
git commit --amend
```
## Cara untuk melihat perbedaan file yang belum di masukan ke staging index
```bash
git diff File_A
```
## Cara untuk membuat branch
```bash
git checkout -b branch test_branch
```
## Cara pindah branch 
```bash
git checkout test
 ```
## Cara merge branch
 git merge master
# untuk mengedit commentar commit 
```bash
git commit --amend
```
- kemudian untuk push ke git repository nya
```bash
git push --force example-branch
```
# Cara setting single repository
```bash
git config user.email "your_email@example.com"
```
```bash
git config user.email
```
# Untuk menghapus branch
```bash
git push origin --delete <branch_name>
```
```bash
git branch -d <branch_name>
```
# Delete Local Branch
 ```bash
 git branch -d branch_name
 ```
# How to create tag
```bash
git tag v1.0.1
```
# How to delete tag
```bash
git tag -d v1.0.1
```

