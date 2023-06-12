1. Create `simple-site`
2. Add `index.html`
3. Initialize repo
4. Add/stage `index.html`
5. Commit 
6. Create `feature1` branch
7. Checkout `feature1` branch 
8. Make some changes:
    - Change `index.html`
    - Add more files `scripts\main.js`
9. Stage changes
10. Commit changes
11. Change back to `master` branch
12. Merge changes from `feature1` branch into `master`
13. Repeat steps 8-12




### Initialize Git Repo
- git init

### Branching & Merging
- Branch
```

git branch FeatureA
git checkout FeatureA
```

- OR 
```
git checkout -b FeatureA
```

### Merging
- Change into the branch you want to merge into 
```
git checkout master
```


- Merge a branch into that branch
```
git merge FeatureA
```