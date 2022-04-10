# Remote Access Tutorial

1. **Installing VSCode**: To install VSCode, we will first go to its official
[website](https://code.visualstudio.com/) and follow their steps. After the
installation, you will be able to see the following start page: \
**Put Image 1 here**

2. **Remote Connecting**: In order to connect to the remote computer, we will
first look up our course-specific CSE 15L [here](https://sdacs.ucsd.edu/~icc/index.php).
Then, on the terminal of the VSCode, type the following command to connect: 

          ssh cse15lsp22[replace specific account here]@ieng6.ucsd.edu

* Then, you will see something like this in VSCODE: \
**Put Image 2 here**

3. **Trying Some Commands**: Then, try to run some commands, such `ls`(listing file),
`cp`(copy),  `mkdir`(make directory), `cd`, or `pwd`, on your terminal. For example, 
after running "ls", your terminal would look like this: \
**Put Image 3 here**

4. **Moving Files with** `scp`: This command would allow you to move a file from your
computer to the remote computer. We first created a file on our computer named "WhereAmI.java".
Then, by the command `scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/`, we would be able to
copy it to the remote computer.\
**Put Image 4 here**

5. **Setting an SSH Key**: Since whenever we connect to the remote computer, we have to enter
the password. The `ssh-keygen` would create a pair of RSA keys (public and private) so that 
the password could be ommited each time. Here is a screen shot of what the set would look like
afterwards:\
**Put Image 5 here**

6.**Optimizing Remote Runnin**: Finally, some commands could be combined to optimize program
efficiency. For example, we could use `;` to connect two commands together. Therefore, the 
most effective way of making a local edits to `WhereAmI.java`, then copying it to the remote
server would be as follows:\
**Put Image 6 here**

