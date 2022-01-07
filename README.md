"#pages-demo" 

git init			#Initialized empty Git repository in D:/GitHub/pages-demo/.git/
git add README.md		#add README.md in .git
git commit -m "first commit"	#提交內容，並附上註解 "first commit"
git branch -M main		#建立git分支，並指派 -M(主要)為 main
git remote add origin https://github.com/Han-Johnny/pages-demo.git	#將專案(origin)上傳至github
git push -u origin main		#將分支 main 上傳至 origin
