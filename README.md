# this is the second test 
 
 1. : init 
 2. : commit
 3. : vranch
 4. : add
 5. : push



echo "# TestInitLog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/kumakumasi/TestInitLog.git
git push -u origin main