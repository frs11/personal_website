# personal_website

Github code (manually)

  Firstly, use git add . to add all the changes.
  Secondly, use git commit -m "message" to commit the changes
  Thirdly, use git push to push the changes
  Fourthly, use git pull to pull any changes made or pull repo


    …or create a new repository on the command line
  
  echo "# first_website" >> README.md    (just to create a readme file)
  git init                               (git initialisation)
  git add .                              (add everything changed)
  git commit -m "message"                (commit with a message)
  git branch -M master                   (setup main brance, one time only)
  git remote add origin https://github.com/frs11/personal_website.git    
              (connect github repository, one time only)

  git push -u origin master               (push to the repository)


  …or push an existing repository from the command line

  git remote add origin https://github.com/frs11/first_website.git
  git branch -M master
  git push -u origin master