1-Tell me how to remove them locally and remotely?
-->LOCAL : use -d optin (fully merged)
  EX: git branch -d test

-->LOCAL : use -D optin (not fully merged)
  EX: git branch -d test

-->REMOTELY : use :
  EX:  git push origin :test

_______________________________________________________
2-Tell me how to checkout another branch without commit 
changes ?
-->STACH
  EX:git stash -->(save changes)
     git checkout test -->(switch to test branch)
     git stash pop -->(retrieve changes)

________________________________________________________
3- Tell me how to list tags?
--> use git tag

________________________________________________________
4-Tell me how to delete tag locally and remotely?
-->LOCAL : use -d optin (fully merged)
  EX: git tag -d "v1"

-->REMOTELY : use :
  EX:  git push origin :v1

_________________________________________________________
5-  Add an image in the README.md file?
-->![git](git.png)







