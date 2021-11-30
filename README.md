### So, what is the new git rule change?  

Simply put, the new git rules will enforce  
- Enforced protected branch (such as main/master), that is  
- Allow forced push (git push -f) for only members with push access (that is, you can bypass the above by using forced push only if you are given the role)  

This will enforce you to push all of your new changes into a branch and use Pull Requests to merge into master/main, thereby protecting it from unstable code changes.

### So how do I push to master now?  

After you create your own branch (from any existing branches, or master), you can still push to the branch the same way you used to do.  
> For example, if I want to add a new econ gui feature, I would make a new branch from econ and add my commits into my own branch.  

When you are ready, simply submit a Pull Request like this and wait for an approval (if you cannot approve yourself, that is). Once it is approved, your changes will be added into master/main with the click of a button like this!

### I see merge conflicts, what do I do?

When there are divergent changes between your development branch and the main branch (the one you are pushing into and the one you need to merge into), you may find yourself with merge conflicts when you try to merge the Pull Request.

Worry not! What you could do is to simply resolve them! It's not that hard.

This is what you need to on Github Desktop.
> Insert Github Desktop procedures here

Alternatively, to prevent merge conflicts, you can merge/rebase the main branch into your developmentment branch before you push the "merge" button. That way, you can resolve the conflicts before they prop up and always make your development branch updated.
