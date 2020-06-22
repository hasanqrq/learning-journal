# GitHub in your PC

We learned how to connect the gitHub to our PCs, starting by install the git on PC and VS studio and workining on them with commands like :

### git add to * add files * 
### git status to * check the directory content*
### git commit -m "the note" *To save as and appy changes*
### git push origin master *to match work on PC with GitHub webite*


# Seeing Your Remotes

By using *"git remote"* we can view short names , for example *"git remote -v'* veiw all remote URLs. *for example:*
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)

we have many parameters like :
 ## *adding Remotes*:
 
 Example:

$ git remote

origin

$ git remote add js https://github.com/janesmith/project1

$ git remote -v

origin https://github.com/johndoe/project1 (fetch)

origin https://github.com/johndoe/project1 (push)

js     https://github.com/janesmith/project1 (fetch)

js     https://github.com/janesmith/project1 (push)
 
 
 ## *Fetching*:
 the code is :
 git fetch [remote-name]
 
 
 ## *Pushing*:
 
 for example :
 $ git push origin master
 
## *Renaming:
for example :


$ git remote rename js jane

$ git remote

origin

jane


## Removing Remotes* :

for example :

$ git remote rm jane

$ git remote

origin


