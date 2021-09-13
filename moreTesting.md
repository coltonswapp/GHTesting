## Want to add all but 1 file to GitHub?

Sometimes it can be desireable to add all your files but 1 single file, or maybe you want to ignore 2 files, or 3 -- a prime use case of this is when your group has been grinding on a project, & someone has been touching the storyboard when they shouldn't have. To avoid conflicts with the storyboard, the person who SHOULD NOT HAVE been touching the storyboard might do something like this, to make sure their changes DO NOT get pushed - hence pushing all their files *but* the Storyboard file.

- [ ] Step 1 is to make sure that you are in the correct directory that is configured with Git.

- [ ] Step 2 is to type the following code:

  ```
  git add .
  ```

- [ ] Step 3 is to add a little bit more onto this line:

  ```
  git add -- . ':!<filename>'
  ```

  
  
  <u>PLEASE use the TAB key when typing the filename so that it gets autocompleted correctly.</u>
  
  
  
  <u>Do not add the '<>', simply enter the filename</u>

- [ ] Want to ignore multiple files? Simply add a comma! 

```
git add -- . ':!<filename>, 
```

