

    echo "# djangogirlsx0930" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin git@github.com:twoutlook/djangogirlsx0930.git
    git push -u origin master
    
    
# Tune up .gitignore    
    git add .
    git status
    git reset
    
    
    git commit -m"init"
    
    git push -u origin master
    
# git tag    
https://git-scm.com/book/en/v2/Git-Basics-Tagging   
    git tag 
    git tag -a v1.0 -m "basic list"
    
    
    twoutlook:~/workspace (master) $ git tag -a v1.0 -m "basic list"

# Create a tag
'''
twoutlook:~/workspace (master) $ git tag
v1.0
twoutlook:~/workspace (master) $ git show v1.0
tag v1.0
Author: twoutlook <twcloudwebapp@outlook.com>
Date:   Fri Sep 30 06:38:24 2016 +0000

    simple post_list
:
tag v1.0
Tagger: twoutlook <twcloudwebapp@outlook.com>
Date:   Fri Sep 30 06:40:46 2016 +0000

basic list

commit 2e5b05c938ed98918de3f321bdb33e131d29d7df
Author: twoutlook <twcloudwebapp@outlook.com>
Date:   Fri Sep 30 06:38:24 2016 +0000
'''

# Push a tag
    git push origin v1.0