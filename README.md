# Homework "BasicSkills"

**Goal:** familiarity with modifying and committing files to a remote GitHub repository through IntelliJ; creating/merging branches according to Gitflow rules; and managing pull requests within GitHub 

**Description:**
1. Open *IntelliJ*. 
1. Go to File -> New -> Project from Version Control:
   1. For URL: Copy the link from the green "Clone or download" button on the Github repo page.
   1. For Authentication: if this is your first time using IntelliJ, follow the prompts to create an authentication token with GitHub or provide a token obtained from https://github.com/settings/tokens Set the expiration date to **after** the final exam date.
   1. Finally, click "Clone" and this will complete the process
1. Create a branch from the main branch and name it "develop" [GH]
1. For each Animal-based class *c* in the “Land” package:
    1. Create a branch from the develop branch titled "feature-*c*" [GH]
    1. Check out the newly created feature branch. [IJ]
    1. Implement a random method in *c* (must compile correctly) [IJ]
    1. Make a commit for the implemented method, commit must have a descriptive comment of at least 12 characters long. [IJ]
    1. Push the change to the branch to your repository [IJ]
    1. Create a pull request to merge your feature branch to the develop branch [GH]
    1. Merge the pull request to the develop branch (do not delete feature branch) [GH]
1. Create and merge a pull request for the develop branch to the main branch (do not delete develop branch) [GH]


**Notes:** It is important to follow the above-specified naming conventions.  Do not make any direct commits to either the main or develop branch, this is not allowed in GitFlow!  If you do more than the required number of pull requests, the grading system will look at the most recent.  This allows you to make up for any pull requests that didn't turn out the way you expected.  Practice on a private repo first.
