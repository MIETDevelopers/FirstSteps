purnendu@purnendu-HP-ProBook-4540s:~$ cd ~
purnendu@purnendu-HP-ProBook-4540s:~$ mkdir my_first_repo
purnendu@purnendu-HP-ProBook-4540s:~$ cd my_first_repo
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ git init
Initialized empty Git repository in /home/purnendu/my_first_repo/.git/
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ echo "first line of code" > a.txt
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ ls
a.txt
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ git add a.txt
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ git commit
[master (root-commit) 9b35f2d] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 a.txt
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ 
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ git remote add origin https://github.com/opensourcemukul/my_first_repo.git
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ git push -u origin master
Username for 'https://github.com': opensourcemukul
Password for 'https://opensourcemukul@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 231 bytes | 231.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/opensourcemukul/my_first_repo/pull/new/master
remote: 
To https://github.com/opensourcemukul/my_first_repo.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
purnendu@purnendu-HP-ProBook-4540s:~/my_first_repo$ 
