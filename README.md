# Study Group Materials: 051721FT

Here are all the notebooks used during study groups!

[Study Group Recordings](https://www.youtube.com/playlist?list=PLKnqdr1Q1F39vbdaMnab2XTsWN2bFsxAB)

If you're getting this repo for the first time:

1. **FORK** and clone this repository (make sure it is the HTTPS url!)
```
git clone https://github.com/[yourusername]/studygroups-051721ft.git
```

2. Add THIS `/yishuen/` version as the upstream (to pull future changes)
```
git remote add upstream https://github.com/yishuen/studygroups-051721ft.git
```

3. After making changes, remember to push your changes to your forked version of the repo:
```
git add .
git commit -m 'message here'
git push
```

### Whenever you want to get updated notes:

1. Make sure your remote is updated with your local changes!

  Either do `git status` to check that everything is up to date, and if not:

  ```
  git add .
  git commit -m 'message here'
  git push
  ```

2. Fetch the changes from my upstream
```
git fetch upstream
```

3. Merge new changes onto your local repo
```
git merge upstream/main -m 'what you updated'
```

4. Push the new notes to your remote repo
```
git push
```
