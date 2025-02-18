# GitAoGitHub

C:\>mkdir repos

C:\>cd repos

C:\repos>dir
 
C:\repos>git clone https://github.com/seuUsuario/seu-repositorio.git


C:\repos>cd GitAoGitHub

C:\repos\GitAoGitHub>git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

C:\repos\GitAoGitHub>git add .

C:\repos\GitAoGitHub>git commit -m ":tada:"
[main 5deb31c] :tada:
 Committer: aluno <aluno@INTRAUECA.CEFET.COM>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 11 insertions(+)
 create mode 100644 index.html

C:\repos\GitAoGitHub>git push


C:\repos\GitAoGitHub>