# Rebase:
* git checkout feature (feature)
* git add .  (feature)
* git commit -m"add file feature1" (feature)
* git checkout master (master)
* git add . (master)
* git commit -m"add file master1" (master)
* git checkout feature (feature)
* git add . (feature)
* git commit -m"add file feature2" (feature)
ici on a : master =>       master1
ici on a : feature => feature1     feature2
* git rebase master (feature)
ici on a : feature => master1 feature1 feature2