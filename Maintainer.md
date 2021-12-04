## So you are a maintainer, now what?


### How do I set the access for individual members?
On Github.com, go to settings/Manage Access, and you should be able to toggle the roles of each member should you be maintainer or admin of the repository.


### What do the roles mean?
There are five roles in GitHub organization.
> Read allows viewing and forking of the repository.
> Triage
> Write allows for making unprotected branches and pushing into them, as well as requesting for merge. However, depending on the branch protection rule they may not be able to push to protected branches.
> Maintainer allows for forced pushes into protected branches, approval of merge requests, and managing other members roles.
> Admin is effectively the owner of the repository and has all access.
You can also consult settings/Repository Roles for details.

### I want to set/unset the protection of a branch, how do I do it?
> To add: On GitHub.com, go to settings > branches, under branch protection rules, you can click on the "add rule" button. Simply put the name of the branch in "Branch name pattern", and choose the appropriate settings below.
> To delete: go to settings > branches and you can edit or delete rules there.

### How do I force push?

### How do I approve merge requests or make comments?

### How much time should I spend on reviewing? How high is the review standard?
Honestly, this is for you to figure out yourself. Our baseline for merging into master is that it doesn't break the game. That aside, whether it is rubber stamping everything or looking over the commit line by line is your choice. That said, once again, make sure the merge request does not break the game 

### I can't do one of the above. Why?
Probably because you don't have the correct role or permission for it. Contact an admin or maintainer for your request.
