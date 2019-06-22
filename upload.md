教學 
https://zlargon.gitbooks.io/git-tutorial/content/remote/sync.html


git config --global user.email "yuchian.eo06g@g2.nctu.edu.tw"  <br>
git config --global user.name "Yu-Chian-Lin" <br>
git add . <br>
git status <br>
git commit -m "modified" <br>
git push -u origin master <br>


branch: 
git branch  // 看當下有幾個branch

git branch version2   // creat  version2

git checkout version2   // 切換 

git add .


new push: 
git init  <br>
git add . <br>
git commit -m "first commit" <br>
git remote add origin  <br>
git push -u origin master  <br>


本地 update :
git fetch origin <br>
git reset --hard origin/master <br>

--------------------
玉勝 
https://github.com/nickandsam20/demo

範例  10 React Native Open-Source Projects You Must Know
https://apiko.com/blog/10-react-native-open-source-projects-you-must-know/