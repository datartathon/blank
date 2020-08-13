# blank
A blank repository to be used as a starting point for hosting a static HTML page using Github Pages.

## Instructions

### Step 1: Clone this repo, and change the repo's origin 
```
git clone https://github.com/datartathon/blank.git
cd blank
git remote rm origin
git remote add origin YOUR_REPO_URL
```

### Step 2: Switch to the gh-pages branch 
```
git checkout -b gh-pages
```

### Step 3: Make changes as needed
It's time to bring your changes over to this repo. You may want to:
- Replace content in index.html with that of your HTML file
- Or add new style files, js files and link them to index.html as needed.

### Step 4: Push your changes to the gh-pages branch

```
git add .
git commit -m "Changed index.html"
git push -u origin gh-pages
```


