To Remove remotely
git push origin :branch_name

to remove locally
git branch -d branch_name

Annotated tags VS lightweight 
-Annotated: used to release versions for applications that can be used
- Lightweight: is just a tage name similar as Aliace to detect

when to use rebase?
-we use rebase when the main get new bases and our branch in the old one so we use it to rebase the new features in main
-when we want to avoid merge commits and keep a clean linear commit structure

-How to list tags?
-git tag

How To Delete Tag locally and remotely?
-remotely: git push origin --delete v1.7
locally: git tag -d v1.7

![picture](https://i.imgur.com/Wfo08Uc.jpeg)