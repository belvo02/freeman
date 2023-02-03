My first readme

Hello!!

learned the use of basic commands like

$ git clone <repo>
$ touch (name of file)
$ git add .
$ git commit -m "Initial commit"
$ git push origin main
  
  
  all started by
  creating a dirctory in my github account
  then 
  pulling a copy of my repository using 
  git clone https://token@github.com/user/alx-pre_course.git
  
  then i navigated to the alx dierctory using 
  cd alx-pre_course/
  I then created this readme file using
  echo 'My first readme' > README.md  
  and then verified its content using
  cat README.md 
  then updated git identity  using
  
  git config --global user.email "you@example.com"
 git config --global user.name "Your Name
  Added the file using 
  git add .
  commited using
   git commit -m "Initial commit"
  then pushed the work to my github using 
  git push
  
  it did not work out, so i first
  searched for day over google
  then had to destroy my sandbox 
  and start afresh to fail again and destroy that same sandbox oncemore
  finally after alot 
  i used
  used git pull
  then git push
  
  
  Then i manipulated and created dirctories using
  mkdir
  touch
  cp
  rm
  rm -r
  mv 
  vi editor
  rmdir
  git status
  git log
  
  then created a brach using 
  git branch update_script
  switched to the brach using git checkout update script
  
  there i manipulated files and folders again
  befor pushing to my github
  
  again it did not work out
  
  after adys of search i found a solution on a forum from 
  
  https://www.freecodecamp.org/news/git-push-local-branch-to-remote-how-to-publish-a-new-branch-in-git/
  
  https://stackoverflow.com/questions/161813/how-do-i-resolve-merge-conflicts-in-a-git-repository
  
  https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts
  
  https://www.simplilearn.com/tutorials/git-tutorial/merge-conflicts-in-git
  
  https://stackoverflow.com/questions/13743468/why-cant-i-push-my-new-branch
  
  https://dev.to/danielcristho/error-pulling-is-not-possible-because-you-have-unmerged-files-how-to-solve-36lc
  
  
  https://stackoverflow.com/questions/26376832/why-does-git-say-pull-is-not-possible-because-you-have-unmerged-files
  
  
  just to highlight a few sources that helped
  
  the found out ihad to set my origin
  using 
git branch -u origin/update_script update_script
  then
  git branch --set-upstream update_script origin/update_script
  
  then git reset –hard origin
  git stash
  
  ...
  after a lot of trial and fail, ifinaöly suceeded.
  and here is my readme.
  
  
  
  
  
