# Creating-repository-in-github-using-https

Steps-

```

1. Create a repository on the local machine
$ mkdir creating-repository-in-github-using-https
$ cd creating-repository-in-github-using-https
$ echo "# creating-repository-in-github-using-https" >> README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git branch -M main

2. Create a GitHub repository and give the repository name as creating-repository-in-github-using-https

3. Add remote repository using the HTTPS URL
$ git remote add origin <Your HTTPS_URL>  
Execute the git remote -v command to check remote repository

4. Use the following command to push the changes to remote repository:
$ git push -u origin main
$ git status

5. Go to github.com and check the remote repository

```
