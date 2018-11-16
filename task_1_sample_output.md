<pre><font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~</b></font>$ cd ~
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~</b></font>$ mkdir my_first_repo
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~</b></font>$ cd my_first_repo
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ git init
Initialized empty Git repository in /home/purnendu/my_first_repo/.git/
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ ls
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ ls -l
total 0
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ echo &quot;first line of code&quot; &gt; a.txt
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ ls
a.txt
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ git add a.txt
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ git commit
[master (root-commit) 9b35f2d] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 a.txt
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ 
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ git remote add origin https://github.com/opensourcemukul/my_first_repo.git
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ git push -u origin master
Username for &apos;https://github.com&apos;: opensourcemukul
Password for &apos;https://opensourcemukul@github.com&apos;: 
Counting objects: 3, done.
Writing objects: 100% (3/3), 231 bytes | 231.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
remote: 
remote: Create a pull request for &apos;master&apos; on GitHub by visiting:
remote:      https://github.com/opensourcemukul/my_first_repo/pull/new/master
remote: 
To https://github.com/opensourcemukul/my_first_repo.git
 * [new branch]      master -&gt; master
Branch &apos;master&apos; set up to track remote branch &apos;master&apos; from &apos;origin&apos;.
<font color="#8AE234"><b>purnendu@purnendu-HP-ProBook-4540s</b></font>:<font color="#729FCF"><b>~/my_first_repo</b></font>$ 
</pre>