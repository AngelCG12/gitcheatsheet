# Cap 2 and 3
//Initialize a git repository: git init.

//Add files: git add --all or you can individually add git add filename.

//Commit files in staging: git commit -m "your message".

//Link local repo with github:

//Create your repository on the github platform

//Copy the https link

//in the folder of your local repo: git remote add origin.

//If you already have everything added to the assembly and you have already made a commitment, you only have to upload it to github with: git push -u origin master

//you should be asked for github username and password

//if you do not have your name and email configured, do it with the commands:

//git config - global username "Your name"

//git config: global user email "your email"

//git branch: See the existing branches and which one you are currently in

//git branch something: Create a new branch called "something"

//git checkout branch_name: changes to the called branch as indicated in "branch_name"

//git fetch: download changes from remote

//git merge branch: merge changes from a branch you are currently on

//git pull: used to download and merge changes from the remote repository

//git log: show the log of your commits in the current branch

//git status: shows the files in staging and the untracked files

//If you need, these are the commands: 

$ git help <verb>
  
$ git <verb> --help
  
$ man git-<verb> --- Example: $ git help config

//git checkout                         To see your files

//git remote -v                        To see URL

//git remote pb                         pb instead of the whole URL

//git remote show origin               To see the origin

//git remote rename pb                 To rename the remote

//git remote rm                        To remove a remote

//git tag -l                            Lists the tags 

//git tag -a v1.4 -m "my version 1.4"    To create a tag

//git tag v1.4-lw                      The commit checksum stored

//git tag -a v1.2 9fceb02              If you forgot to tag

//git tag -d nameofthetag               To delete a tag

$ git mv README.md README /* After you have created several commits, or if you have cloned a repository with an existing commit history, you’ll probably want to look back to see what has happened. The most basic and powerful tool to do this is the command. / $ git log //Useful options for git log --pretty=format //Option Description of Output / %H--Commit hash

%h-- Abbreviated commit hash

%T--Tree hash

%t--Abbreviated tree hash

%P--Parent hashes

%p--Abbreviated parent hashes

%an--Author name

%ae--Author email

%ad--Author date (format respects the --date=option)

%ar--Author date, relative

%cn--Committer name

%ce--Committer email

%cd--Committer date

%cr--Committer date, relative

%s--Subject*/

/This command takes your preparation area and uses it for confirmation. If you haven't made any changes since your last commit
