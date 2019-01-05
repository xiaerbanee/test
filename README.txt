 test
 First, you login Github.com with your own account, then create a repository in Github.com.
 Second, in you local computer make a directory and give it a name, such as pyfile.
 Third, cd this directory, and execute "git init" command to initiate a git repository.
 After this, execute the following command

 echo " test" >>README.md
 git add README.md
 git commit -m "first commit"
 git remote add origin "git@github.com:xiaerbanee/test.git"
 git push -u origin master
