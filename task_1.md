## Step 1:
Create a GitHub account.  

## Step 2:
Install git
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Step 3:
Customize Git Environment  
Run the following in shell:  
```sh
$ git config --global user.name "Your user name"
$ git config --global user.email "your_email@email_service_provider"
```
Now, check if the environment is set or not:  
```sh
$ git config --list
```

## Step 4:
Create your first repository  
Run the following in shell:  
```sh
cd ~
mkdir my_first_repo
cd my_first_repo
git init
```

## Step 5:
Add a new file to your repository  
Run the following in shell:  
```sh
echo "first line of code" > a.txt
git add a.txt
git commit
```

## Step 6:
Host your repository on Github.com  
Create a GitHub repository  

## Step 7:
Push your local repository to the one created on GitHub  
copy the below command for your repository from GitHub webpage  
```sh
git remote add origin https://github.com/opensourcemukul/my_first_repo.git
git push -u origin master
```

## Step 8:
Check https://github.com/opensourcemukul/my_first_repo  
to confirm.  
Great! Now you have created and hosted your repository on GitHub.com  
