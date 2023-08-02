```
2004  git init
 2005  ls -1
 2006  cd git_tut
 2007  git init
 2008  ls -a
 2009  git status
 2010  touch README.md
 2011  git add README.md
 2012  git status
 2013  git log
 2014  git config -global user.name siddharth-kothari9403
 2015  git config --global user.name siddharth-kothari9403
 2016  git config --list
 2017  git config --global user.email siddharthvatps@gmail.com
 2018  git config --list
 2019  git status
 2020  git init
 2021  git status
 2022  git commit -m "initial commit"
 2023  git log
 2024  git remotr add origin https://github.com/siddharth-kothari9403/git_tut.git
 2025  git remote add origin https://github.com/siddharth-kothari9403/git_tut.git
 2026  git branch -M main
 2027  git branch
 2028  git push -u origin 
 2029  git push -u origin main
 2030  git branch
 2031  git checkout -b new-feature
 2032  git branch
 2033  touch new.txt
 2034  echo "hi" > new.txt
 2035  cat new.txt
 2036  git commit -m "new feature"
 2037  git add new.txt
 2038  git commit -m "new feature"
 2039  git status
 2040  git push -u origin new-feature
 2041  git status
 2042  git switch main
 2043  git checkout main
 2044  git branch
 2045  git checkout new-feature
 2046  git checkout main
 2047  git merge new-feature
 2048  git branch
 2049  git push -u origin main
```
