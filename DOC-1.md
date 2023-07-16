<<<<<<< Updated upstream
=======
We are testing the use of git (and GitHub) as a document management system.

To do this, we are first going to add branch protection rules.

1. Require pull requests before merging
	1. This will act as our change request system.
2. Require approvals on those pull requests.
	1. Starting with 1 approval
3. Require commits to be *signed*.
4. Do not allow bypassing the above settings.

This only applies to main - this means *main* is effectively the controlled QMS directory.

Now that we've done this, it should *not* be possible to push to main.

Great! It worked. Push, even forced, was declined.

so, now we need to sign - *and* we need to use a pull request.

SO we geenerate a key, add it to github
and change git to use it

and then we add -S to sign a commit.... and it should still not let us push! 
A side effect here is that *every* commit has to be signed. Not that helpful. Better if every PR is signed.

But anyway. PR!
>>>>>>> Stashed changes
