# Team_Gray-workflow

Ariella Mordukhayeva - Contributor  
Sukanya Raj - Contributor  
Sajarin Dider - Maintainer  

## WIL: Creating Forks 

I learned how to connect my fork with both the original repo (the upstream) and my remote copy of the repo (the fork). I also learned how to verify if I sucessfully added the remote by using the command ``` git remote -v ```

Fortunately, the instructions were clear enough so there were not major issues. 

## WIL: Creating Issues 

I learned how to add issues to a repository, and I learned that multiple people can create issues at the same time. 

## WIL: Fixing The First Issue 

I learned that Github can use keywords in your commit message like ``` fixes #10 ``` to automatically reference a specific issue (In this case, issue #10). To fix an issue you have to first pull the latest version from the upstream using the command ``` git pull upstream master ```, then update your clone repository using the command ``` git push origin master ``` and then make your changes. After making your changes, you then push to your fork (origin) using ``` git push origin master ```. Now that your origin is a commit ahead of the upstream, you can make a pull request. 


## WIL: Fixing Remaining Issues

Fixing the remaining issues was easy enough. One of our team members Sukanya was having some weird issues with their fork near the end of the class session. The fork was behind the upstream somehow. I believe the issue got resolved however. I learned how to add other Github members as collaborators and how to give others certain permissions. This is not useful to me now, but may be useful if I am ever in charge of a large open source project requiring me to assign different levels of power for contributors. 
