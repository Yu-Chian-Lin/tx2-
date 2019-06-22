教學 
https://zlargon.gitbooks.io/git-tutorial/content/remote/sync.html


git config --global user.email "yuchian.eo06g@g2.nctu.edu.tw"
git config --global user.name "Yu-Chian-Lin"
git add .
git status
git commit -m "modified"
git push -u origin master


branch: 
git branch  // 看當下有幾個branch

git branch version2   // creat  version2

git checkout version2   // 切換 

git add .


new push: 
git init 
git add .
git commit -m "first commit"
git remote add origin 
git push -u origin master 


本地 update :
git fetch origin
git reset --hard origin/master

--------------------
玉勝 
https://github.com/nickandsam20/demo

範例  10 React Native Open-Source Projects You Must Know
https://apiko.com/blog/10-react-native-open-source-projects-you-must-know/