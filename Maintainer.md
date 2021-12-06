## So you are a maintainer, now what?

### How do I set the access for individual members?
On Github.com, go to settings/Manage Access, and you should be able to toggle the roles of each member should you be maintainer or admin of the repository.
![image](https://user-images.githubusercontent.com/77932983/144914808-f96aa901-8718-43dc-909f-6e9e330f9249.png)

***

### What do the roles mean?
There are five roles in GitHub organization.
> Read allows viewing and forking of the repository.  
> Triage allows managing issues and pull requests (but not write yet).  
> Write allows for making unprotected branches and pushing into them, as well as requesting for merge. However, depending on the branch protection rule they may not be able to push to protected branches.  
> Maintainer allows for forced pushes into protected branches, approval of merge requests, and managing other members roles.  
> Admin is effectively the owner of the repository and has all access.  

#### You can also consult settings/Repository Roles for details.

***

### I want to set/unset the protection of a branch, how do I do it?
![image](https://user-images.githubusercontent.com/77932983/144915397-6a2c1617-ff50-4676-aadf-a9eddd956f87.png)

> To add: On GitHub.com, go to settings > branches, under branch protection rules, you can click on the "add rule" button. Simply put the name of the branch in "Branch name pattern", and choose the appropriate settings below.
![image](https://user-images.githubusercontent.com/77932983/144915485-6954afdd-d4ef-49b8-8b2d-449185e158ed.png)
##### For this demonstration repo, this is the only option I chose. (And hopefully this is also the only option you need).


#### To delete: go to settings > branches and you can edit or delete rules there.

***
### How do I force push?
#### Github Desktop: https://stackoverflow.com/questions/46866009/is-there-a-force-push-option-in-github-desktop  

There is no forced push on Github.com. Also, if you are using a terminal, why are you even asking this question. "git push -f"
***
### How do I approve merge requests or make comments?
#### You can add comments (and @ ppl) at the bottom of the merge request like this:
![image](https://user-images.githubusercontent.com/77932983/144916012-d150af38-80ba-47cc-90e8-b0767cd5e48e.png)


#### To review a merge request, click here :
![image](https://user-images.githubusercontent.com/77932983/144916276-985f0fd2-76ca-4c6f-8c80-ecc6aa2dc586.png)

#### which will lead you to something like this:
![image](https://user-images.githubusercontent.com/77932983/144916397-cb714438-2da4-4063-a2d7-212f6bdae533.png)

#### To approve, simply do this:
![image](https://user-images.githubusercontent.com/77932983/144916500-2fbea6e0-61b5-4250-9702-e650151bd78f.png)

#### Other options are also shown should you choose to use them.

***
### How much time should I spend on reviewing? How high is the review standard?
Honestly, this is for you to figure out yourself. Our baseline for merging into master is that it doesn't break the game. That aside, whether it is rubber stamping everything or looking over the commit line by line is your choice. That said, once again, make sure the merge request does not break the game 
***
### I can't do one of the above. Why?
Probably because you don't have the correct role or permission for it. Contact an admin or maintainer for your request.
