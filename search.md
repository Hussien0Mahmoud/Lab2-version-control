
Hussien Mahmoud Mohamed Ahmed

-----------------------------------------
==> delete commands ?

-git branch -d test 
-git branch -d dev
git push origin --delete  test
git push origin --delete  dev

------------------------------------------------
==> Annotated tags vs Lightweight Tags ?
** Annotated tags: 
Used for creating a detailed, permanent record
-Stored as a full Git object in the repository.
-Suitable for official releases or milestones.
ex)->  git tag -a v1.0.0 -m " stable release"

**  Lightweight Tags:
A simple reference to a commit, often used for quick or temporary tagging.
-Essentially just a pointer to a commit.
-Does not store any metadata, such as a message or author details.
-Created faster and consumes less space.
-Suitable for internal or informal purposes.
ex)-> git tag v1.0.0

------------------------------------------------------------------------------
==> When to use Rebase ??
1- To Keep a Clean, Linear Commit History
git checkout feature-branch
git rebase main

2-When Working on a Feature Branch
git checkout feature-branch
git rebase main

3-To Update Your Branch with Upstream Changes
git pull --rebase origin main

4-To Edit or Reorganize Commits
git rebase -i base-branch

5-To Remove Undesired Commits

----------------------------------------------------
How to list tags?
-git tag
------------------------------------------------------
How to delete tag locally and remotely?
-delete tag locally
git tag -d v1.0.0

-delete tag remotely
git push origin --delete v1.0.0

-------------------------------------------------
Bonos:
![image](https://img.freepik.com/free-photo/flatlay-outfit-travel_53876-138233.jpg?uid=R71403269&ga=GA1.1.1887001370.1728162276&semt=ais_hybrid)
