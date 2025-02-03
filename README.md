git --version
git config --global user.name "Guler Yolcu"
git config --global user.email "guleryolc@outlook.com"
mkdir proje.12.1
cd proje.12.1
git init
echo "merhaba git" > dosya.txt
git status
echo "merhaba git" >note01.txt
git status
git add dosya.txt
git status
git commit -m "ilk commit"
git remote add origin https://github.com/guleryolcu/proje.12.1.git
git branch -M main
git log --oneline
git clone https://github.com/guleryolcu/proje.12.1.git
 git branch yeni-ozellik
 git checkout yeni-ozellik
  git checkout -b yeni-ozellik
  git merge yeni-ozellik
 git checkout yeni-ozellik
git rebase main
git cherrt-pick <120a07d>
git reset --soft <120a07d>
git reset <120a07d>
git reset --hard <120a07d>
git revert <120a07d>
git stash
git stash pop
git stash list
git add <dosya.txt>
git commit -m "Conflict çözüldü
git checkout -- <dosya.txt>
