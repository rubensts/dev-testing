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

- create a feature branch:
  ` git branch [name-of-your-feature-branch]
git checkout [name-of-your-feature-branch]`
- make the changes and save

## Stage, commit and push the changes you made

- Staging `git add .`
- Commit `git commit -m "added text to readme"`
- Pushing - IMPORTANT
  - Pushing to the UPSTREAM
    `git push -u upstream [name-of-your-feature-branch]`
  - Pushing to MY main
    `git push -u origin [name-of-your-feature-branch]`

### Result

- First time didn't work, trying for the second time
