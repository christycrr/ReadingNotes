Read3GithubCommands
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/test

To clone a repository into a directory with another name of your choosing, use the following command format:

$ git clone https://github.com/test mydirectory

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory Example:

$ cd test (cd = change directory) Use the git init command $ git init $ git status

Track all files in a repository by using the following command:

$ git add * $ git commit -a *This command commits a snapshot of all modifications to tracked files in the working directory. Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example:

$ git push origin master
