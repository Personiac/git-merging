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




### Reference

- https://github.com/craigmckeachie/yearup-pgh-spring-2023/tree/main/git

- https://gist.github.com/craigmckeachie/3376f54b1f471ca3e2b9fe5390eddb39

### Branching

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