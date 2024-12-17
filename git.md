ssh keys:


====
data = public+private 

private key - Lock . 
public key - key (anyone) 

1. Create account in Github . 
2. SSH keys . 
3. Add your public key in Github. 
4. Install Git bash . 
5. if possible install WSL (windows sub system for linux) - Ubuntu. 
6. if possbile create free account either in Cloud. 


==== 
Day 3:
17/12/24
- Branches.
- Branching types
- Pull Request - Developer
- Merge - Reviewer will review and merge code . 
- Branch Protection & Policies. 

1. Starting 
git clone , 
git add .
git commit 
git push 

2. Creating branches. 
to created 
git checkout -b <new branch>
make code changes
git add .
git commit -m "message"
git push --set-upstream origin vm # git push to remote branch 

3. enhance code in the existing branch. 
Shaice done existing code. 

4. merge code :
PR request. 

merge code to master 

5. Branching types


all production to main

dev, and pre-prod 

Single branch source of truth. 

1. dev and pre-prod and prod can also uses main branch . 

Trunk based branching . 

1. Dev - dev branch . 
2. pre-prod -> pre-prod branch 
3. prod - main branch . 




