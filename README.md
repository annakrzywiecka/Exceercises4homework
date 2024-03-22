# Exceercises4homework
Anna Krzywiecka 21.03.2024 This git repository is about git
# GITHUB
## Starting
1. First step


'''  
git config --global user.name "your_username"  
'''


2. Second step


'''  
git config --global user.email youremail@example.com  
'''


3. Third step


'''  
git clone 'https.or.ssh.of.repository.on.github.'  
'''


## Basics 
* add
* commit
* push


When you **add** always choose files to track or simply write a dot (.) which stands for all files in the directory

When you **commit** add '-m Your message' which will appear as a header in github 

When you **push** add 'origin ChosenBranch' when it is your first time pushing. Next times it is as simple as 'git push'. Then your changes will be visible on your github

## Checking differences between versions

* git diff

It is important to write which versions to compare, e.g 'git diff main..OtherBranch'

## Adding new branch

* git branch NameOfBranch

* git checkout NameofBranch

* git merge NameOfBranch

**git branch** creates a new branch, **git checkout**  changes to the branch and **git merge** if you want to change main with the new branch

Attention! Previous versions can be also used just like the branches with **git checkout** and **git merge**

## Others

* git log

It shows all commits
