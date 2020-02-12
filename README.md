## Learning Git

You want to read this before you use this


### How to make a GitHub repo

Step 1: Save your project  
  
Step 2: Run 
```
git init
```
Step 3: Run this for all files
```
git add . 
```
or run this for an individual file
```
git add 'filename' 
```
Step 4: Run 
```
git commit - m "Your comment here" 
```
Step 5: Login to gitHub -> New Repo -> Name it -> Copy commands to push to repo (below 2 lines)  
  
Step 6: Run
```
git remote add origin CopiedURL
```
Step 7: Run
```
git push -u origin master
```

<br/><br/>


### How to push code to your repo after its set up

Step 1: Run this for all files
```
git add . 
```
or run this for an individual file
```
git add 'filename' 
```
Step 2: Run 
```
git commit - m "Your comment here" 
```
Step 3: Run 
```
git push
```

<br/><br/>

### How to stash

Step 1: Run
```
git stash
```

Step 2: Switch to your other branch and work with code, switch back to branch with stash

Step 3: Run below to see stash list
```
git stash list
```
Step 4: Run below to see stash changes
```
git stash show
```
Step 5: Run below pull stash back into branch
```
git stash apply
```