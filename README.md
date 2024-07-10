# dev-testing

## Steps I followed

- fork the original repo
- clone the repo to my local machine
- sync changes with main repo
  - `git remote add upstream`, paste the URL and hit Enter.
- verify my remote repo
  - `git remote -v` and hit Enter.
- result:

  - ```
       $ git remote -v

       > origin    https://github.com/YOUR-USERNAME/YOUR-FORK.git (fetch)
       > origin    https://github.com/YOUR-USERNAME/YOUR-FORK.git (push)
       > upstream  https://github.com/ScrimbaBootcamp/project-tracker.git (fetch)
       > upstream  https://github.com/ScrimbaBootcamp/project-tracker.git (push)
    ```

  ```

  ```

- Keeping the branch up to date - VERY IMPORTANT!
  `git pull upstream main`
- Update those changes to YOUR fork
  `git push origin manin`
- create a feature branch:
  `git checkout -b [name-of-your-feature-branch]`
- NOW proceed to make the changes and SAVE

## Stage, commit and push the changes you made

- Staging `git add .`
- Commit `git commit -m "added text to readme"`
- Pushing - IMPORTANT
  - Pushing updates only to the corresponding branch on the remote
    `git push`
  - Pushing to the UPSTREAM
    `git push -u origin [name-of-your-feature-branch]`

## Submit a pull request

- Proceed with requesting a pull request in the project's main repo (upstream)
- Once the pull request has been accepted, you can delete the feature branch
  `git branch -d [name-of-your-feature-branch]`

### Result

- First time didn't work, trying for the second time
- Second time it worked, but I needed permission from the owner.

### Correcting

- The correct way to push to the upstream is to use:
  `git push -u origin [name-of-your-feature-branch]`
- The info has been corrected to this file
