[![Build Status](https://travis-ci.com/apreshill/bookdown-travis-production-context.svg?branch=master)](https://travis-ci.com/apreshill/bookdown-travis-production-context)

To follow along:

1. [Make a repo on GitHub](https://happygitwithr.com/new-github-first.html#make-a-repo-on-github-2)

1. [Create a new RStudio Project via git clone](https://happygitwithr.com/new-github-first.html#new-rstudio-project-via-git-clone)

1. In your R console, enter:

```
bookdown:::bookdown_skeleton(getwd())
```

**Follow my lead!**

+ [Travis + Netlify](link tbd)

**My Travis build logs:**

+ [Build #1: Build the book only](https://travis-ci.com/apreshill/bookdown-travis-production-context/builds/98674044)

  ```
  Output created: _book/index.html
  [1] "/home/travis/build/apreshill/bookdown-travis-production-context/_book/index.html"
  The command "Rscript -e 'bookdown::render_book("index.Rmd")'" exited with 0.
  
  store build cache
  
  Done. Your build exited with 0.
  ```

+ [Build #2: Build the book and deploy to Netlify production context only](https://travis-ci.com/apreshill/bookdown-travis-production-context/builds/98676936)

  ```
  Output created: _book/index.html
  [1] "/home/travis/build/apreshill/bookdown-travis-branch-deploy/_book/index.html"
  The command "Rscript -e 'bookdown::render_book("index.Rmd")'" exited with 0.
  
  store build cache
  
  Installing deploy dependencies
  
  Preparing deploy
  Deploying application
  Done. Your build exited with 0.
  ```
  
  + Deployed! https://bookdown-travis-production-context.netlify.com/
