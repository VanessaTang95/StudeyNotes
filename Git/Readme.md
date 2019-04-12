# Problems I met while programming -- Git version

##### pathspec 'master' did not match any file(s) known to git
* When: cloned an empty repo to local path
* Solution: need to have a branch then to `checkout`
  ```
  git checkout -b master
  git checkout master
  ```
  
