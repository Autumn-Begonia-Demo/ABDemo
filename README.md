### **So, what is the new git rule change?** 

Simply put, the new git rules will enforce  
- branch protection (such as main/master), that will not allow commits into master directly.
- Instead, you will be pushing into a development branch and submit a merge request and obtain approval in order to make your work into the mod release.
- Allow forced push (git push -f) for only members with maintainer or admin role (that is, you can bypass the above by using forced push only if you are given the role).  

This will enforce you to push all of your new changes into a branch and use Pull Requests to merge into master/main, thereby protecting it from unstable code changes.

> Note 1: This note is mostly designed for users of Github.com or Github Desktop. If you use terminals like Git Bash then feel free to ignore the tutorials. You are based and I should not be telling you what to do with your life, assuming you already know what you are doing.


> Note 2: The roles mentioned here are only applicable when the repository is owned by an "organization" account, which I urge that we transfer to one immediately.

***

### **So how do I push to master now?**

After you create your own branch (from any existing branches, or master), you can still push to the branch the same way you used to do. Then, you will need to submit a pull request (aka merge request) back into master to integrate these commits.

#### **Your development should be done primarily in branches unless otherwise instructed.**
> For example, if I want to add a new econ gui feature, I would make a new branch from econ and add my commits into my own branch.  

***

#### **How do I create a branch?**

#### For Github Desktop users, do this:
Creating a branch: https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#creating-a-branch  

Make sure you do not forget to publish your branch! https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#publishing-a-branch  

Switching branches: https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#switching-between-branches  

Deleting a branch: https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches#deleting-a-branch  

If you are using Github.com, this should be intuitive.  
![image](https://user-images.githubusercontent.com/77932983/144911956-45726cea-661a-4f9c-904f-facbf0a2dbef.png) 

***

### **How do I submit a pull request?**
When you are ready, simply submit a Pull Request like this and wait for an approval (if you cannot approve yourself, that is). Once it is approved, your changes will be added into master/main with the click of a button like this!

#### For Github Desktop users, do this: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request  
You will (probably) need the review and approval of (at least) one maintainer. See here for how to request reviews: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/requesting-a-pull-request-review  

#### If you are using Github.com instead, click on "Pull Requests" which should lead you here.![image](https://user-images.githubusercontent.com/77932983/144913094-4ffcb192-3364-4b6c-8b0e-11b68236c85a.png)
Then click "Create new Pull Request" which should lead you here. ![image](https://user-images.githubusercontent.com/77932983/144913215-b7c1b531-297f-451b-bb94-d2e106796aff.png)

You will see this interface when you choose the branch you want to merge into as "base", and your development branch as "compare". Then, click "create pull request" after you finished reviewing changes. Afterward, you may see an interface like this. ![image](https://user-images.githubusercontent.com/77932983/144913595-b64592a2-c468-4097-88b0-ef02c3f230dc.png)

It may look different to you, as you are probably not an admin (unless you are), which means you will need to gain approval to merge. Click on this to request reviews from people. ![image](https://user-images.githubusercontent.com/77932983/144913745-92b3ddc5-fc9d-4b52-a815-b77f0483ea53.png) When they approve, you will see the merge button turn green and you will be able to merge it. 

## Voila, you have now merged your changes!

***

### I see merge conflicts, what do I do?

When there are divergent changes between your development branch and the main branch (the one you are pushing into and the one you need to merge into), you may find yourself with merge conflicts when you try to merge the Pull Request.

Worry not! What you could do is to simply resolve them! It's not that hard.

#### This is what you need to on Github Desktop: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github

tldr: simply resolve the conflicts (you can see conflicted files indicated by the error message) which will be enclosed with "=====" or "<<<<<" or ">>>>>". Edit these files to your liking and get rid of these enclosures and save. You can click on "Mark as resolved" on Github Desktop.

Alternatively, to prevent merge conflicts, you can merge/rebase the main branch into your developmentment branch before you push the "merge" button. That way, you can resolve the conflicts before they prop up and always make your development branch updated.

### For the guide for maintainers and admins, you can look to maintainer.md in the same folder as this file.
