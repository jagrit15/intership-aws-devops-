# Git

1. Git Config
    git config --global user.name " "
    git config --global user.email "  "
    git config --list

2. Init and setup
    Git init
    Git clone " "

3. Oper on files
    Git add "file"
    Git add .
    Git reset " "
    Git commit -m
    Git diff

3. Branching and merging
    Git branch [branch name] (create new) 
    Git checkout [branch name](leave the branch)
    Git checkout . (reset changes in all files)
    Git switch -c [branch name]
    Git merge [branch]
    Git log

4.  Tags
    git tag(lightweight tag)
    git tag -a "name" -m "msg"
    git show tag "name"
    git tag -d "name" (delete)
    git push origin "name"

5. push to github 
    git push 
    git push origin "branch name"

6. git cherry-pick [hash value]

7. git rebase [branch-name]

8. git stash
   git stash pop
   git stash -m "comment"
   git stash list 
   git stash pop --index [no.]
   git stash clear (clean all stash)
   git stash drop stash@{0}
   git stash list  

9. git grep [] (use to search in git repo)  

10. git rev-list --count main
    (give no. of commits made)

11. git diff [file]
    git  diff --staged [file](use to check git add befor changes)

12. git reset [file]

13. git revert [hash-value] (reverts commits in github)

14. git fetch then merge = git pull
    (git fetch get file on local repo not in working dir but when applying merge it reflects in dir too)

15. git remote add origin [repo-link](add local project into github)
    git remote -v(check remote repo)
    



# jenkins

1. job creation
2. job configuration 
3. plugins(blue ocean, git)
4. jenkins role based access control
5. upstream and downstream
6. built periodically
7. poll scm(check git)
8. enviornment variable
9. global variable(GLOBAL_VAR) 
10. parameterized job
11. concurrent job
12. pipeline creation
13. slave master concept
14. post actions
15. git intergration
16. credentials
17. jenkins install on server(aws)
18. git intergreation with git(web-hook) 
19. cloning git repo with jenkins into local

# aws
1. aws cloud practitioner essentials certificate
2. ec2
3. AMI (amazon machine image)
4. aws load balancer
5. classical load balancer
6. added load balancer http in security rules
7. auto scaling(vertical and horizontal)
8. aws s3
9. srr and crr
10. S3 storage classes
11. s3 encryption 
12. cloudfront
13. AWS IAM
14. aws vpc
14. creating subnets
14. cidr with ip 
15. dynamo db 
16. cloud watch
17. alarms 
18. custom metrices
19. billing alarm
20. cloud formation 
21. template creation 
22. vpc template
23. securtiy group template
24. ec2 templete

# linux
1. sudo poweroff (stop instance)
2. stdin, stdout, stderr(<, >, 2>)