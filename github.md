# Introduction to Github
This article seeks to cover in details the following; 



1. What is GitHub
2. Why GitHub
3. Git vs. GitHub
4. Clone (Show how to do cloning)
6. Pull request (Show how to do a pull request)
7. Commit (Show how to do a commit)
8. GitHub Desktop vs. Github CLI


Whenever we start working on a project, the question that arises is how do we manage the history of this project and track the progress we are making and also avoid losing our work. This is the problem that git and github seeks to provide solution to. Through this writing, we seek to provide  step by step guide on how we can utilise git and github in tracking changes on our project and also making useful contributions to the project of others and also connecting with fellow developers across the globe.


 ## What is GitHub?
Clearly the word GitHub comprises two important words git and hub. 

GitHub is a platform for hosting git repositories on a remote server or on the internet. It makes connecting with other developers across the globe easy. It is possible to enhance your skills by also contributing to Open source  projects of others via GitHub also known as Open source contribution and sharpen your skills. Github is highly dependent on git so whenever you hear github, know that git is in the  background. 

You may be wondering what Git . I will help you understand this in a moment. *Git  is an open source project that developed by Linus Torvalds in 2005.* It is a distributed version control system(DVCS) meaning that a mirrored copy of the entire codebase and history is available in the developers local machine of the developer. In terms of popularity, Git is the most adopted version control system globally. 

Git is compatible with various Operating Systems and this has led to its high adoption. 

To install git on your local machine is very easy, just visit [this link](https://git-scm.com/)









## Git vs Github

Although used together, there are differences between Git and GitHub. I will be outlining a few of them.
It is worthy to note that git does not require an internet connection so you can secure your project from where ever you are but to save your work on  GitHub connection to the internet is necessary. Unlike Git which is a software,  GitHub is a service. Git is distributed while github is centralised. With Git users data is not managed while github has a provisiion to
manage user data. git is open source while github has both free and paid services. git was released in 2005 while github was released in 2008. You can install git on your local machine. github is hosted on the cloud. through github one can connect with other developer
while git does not make that provision to connect with others.

Github allows us to acccess the repository of others but we cant access the repository of others through git. git  is a tool and can be considered as the foundation on which github is built. Git is a tool while github is a service for hosting our git repository.


Clone (Show how to do cloning)
git clone is used to clone a repository that already exist either on the cloud or on your local machine into another folder that that youve created. it provides you with all the 
files and history of th0e codebase in your device. You can perform git clone easily using HTTPS or SSH code. Let me show you how. Visit the repository you want to clone by searching for 
its name, opening it and clicking on the code button located on the right side of the screen  just beside the "Go to file" and "add file". then copy th HTTPS or SSH url. In your terminal, create a folder you would like the desired repository to be in. 
Type mkdir js-syntax
Move into the folder using cd js-syntax
Thirdly, type  git clone  and paste the url Its a very easy processs.

It is worthy to note that we can only make changes to the file we have cloned only if we have write permissions to the repository. This is because without this restriction, someone can easily access the file another file and make changes that may not be desired or needed by the project owner.

### Commit (Show how to do a commit)

Git commit is always preceded by a very popular command known as the git add. Imagine the git add as a command used to bring all the files we want to take a snapshot of to the stage. The git commit is the command that takes the snapshot.
then takes a snapshot of the files that has been brought to the stage where the camera is. Any file that is not on the stage will not be committed. You only have safe version of committed files, that can be changed only when we ask git to do so.

git commit -m "This is how to commit"   The flag m stands for message.
we can also use git commit -a -m "Enter your message here". The -a stands for all.

Errors in the commit message can be overwritten using the git commit --amend “correct message”


Pull request (Show how to do a pull request):

Collaborating with others is great. At thesame time, effective collaboration involves communication. Pull request affords the contributor the means for to tell the project owner about a change that has been made and also tells the project owner to check the changes and decide whether to accept the change or decline. It is used for effective communication. Pull request can be carried out using either of GitHub, GitHub Desktop and GItHub CLI etc. Once you have made a pull request, there will appear a page that compares the two branches to see the difference that are there. To demonstrate this very quickly

Start by clicking the fork button on the repository page. Forking gives you a copy of the codebase you can work with without affecting the original codebase. After that, follow the clone process described above.

Lets say you found a repository with a spelling error and would like to correct it.

Enter git checkout -b “correct-spelling-error” in your terminal after cloning the project. This command creates a new branch. Go to the file where you want to make changes and perform the change. 
Type the following one after the other 
“git status” to see the files you have modified
“git diff” shows the differences between the branches
“git add” the name of the file that you modified
 git commit -m “made spelling correction”
git push origin correct-spelling-error

Then go back to github you will find a green button that says “compare and pull request” click it and give a descrription of the change you made and create a pull request. 


### GitHub Desktop vs. Github CLI
Both git and github seeks to achieve one thing which is making it easier for developers to work with git and github and also increasing the efficiency of developers.
Github Desktop
Github desktop in one sentence simplifies your work and makes it easier to work with repository both on your local machine and those 
hosted on the cloud. The goal is to increase the work speed of software developers and take off all the hitches that may be 
attached to working with git and github. To have it installed on your local machine just visit [here](https://desktop.github.com/)
and download the one that fits  your Operating system. One of the things you can do with github desktop is to clone repositories
both local and those hosted on the internet using URL. by doing this, the file is automatically stored on a Github folder it creates on your device.

### GitHub CLI

When you think about ease, just think about github cli. This open source tool allows you to use github in the terminal the terminal and completely takes out the 
need for constant switching from the terminal to the cloud or github desktop. The github cli stands for github command line interface. tHe entire idea behing github cli is to
integrate git and github in the terminal so if you are like me and dont enjoy switching betweeen git and github just have this installed. Another advantage of using the github cli is that it enables 
the user to get familiar and comfortable working with the terminal which is a very requisite ability for developers. I mean who doesnt like the feeling of being a hacker.

To install GitHub CLI is very easy just visit the https://cli.github.com/

In conclusion, with this that we have covered so far, i am convinced that you will be able to keep track of the projects thaat you are working on and also be able to contribute to other open source projects that are freely available.
