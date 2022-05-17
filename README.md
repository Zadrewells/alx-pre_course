 echo 'My first readme' > README.md   
cat README.md  
 git config --global user.email "zadrewells@gmail.com"
 git config --global user.name "Zadrewells"
 git add .
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:Zadrewells/alx-pre_course.git
git push -u origin main
