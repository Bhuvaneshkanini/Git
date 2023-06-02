# Git

-----------------------------------------------------
#To Create a Branch
-----------------------------------------------------
1.Create local branch:

git branch <<#new-Branch-name>>
  
i.e)git branch Check-brach

2.Push the Branch into Remote
git push --set-upstream origin my-branch

------------------------------------------------------
#To Delete the Branch
------------------------------------------------------
1.Delete the Branch in Local
$ git branch -d <branch-name>
i.e)$ git branch -d new-branch-name

2.Delete the Branch in remote
$ git push origin --delete <branch-name>
i.e)$ git push origin --delete new-branch-name
