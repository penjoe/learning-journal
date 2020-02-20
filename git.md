# Get Started with Git!

| [Table of Contents](https://penjoe.github.io/learning-journal/) | [Growth Mindset](https://penjoe.github.io/learning-journal/growth-mindset) | [What is Markdown?](https://penjoe.github.io/learning-journal/markdown)  |  [Tools of the Trade](https://penjoe.github.io/learning-journal/coders-computer) | [HTML Structure](https://penjoe.github.io/learning-journal/html-structure) | [Styling with CSS](http://penjoe.github.io/learning-journal/css) | [Computer Architecture and Logic](https://penjoe.github.io/learning-journal/comp-logic) |

Git is a robust yet lightweight version control system that developers use to keep track of their projects locally. It keeps a record of any changes made and allows messages to be inserted detailing why a change was made. It can easily be used in tandem with GitHub or a local network to seamlessly collaborate on projects. Git is a great tool that is widely used in the industry to keep projects from getting too messy. It's accessed primarilly through terminal and uses basic comands to navigate, update and add/delete repositories.

Workflow with Git is simplified by this acronym:
+ **A**dd
+ **C**ommit
+ **P**ush

A.C.P. is how to maintain consistency in your workflow. When working on a project in a text editor or IDE, changes to files will be made. This files must first be added to Git with the `git add` command. This will tell Git that there are changes made and that we are ok with those changes. Next, those changes need to me commited, or saved, with the `git commit` command. Adding a `-m` flag to `git commit` will allow you to add a message detailing why a change was made. Once a change has been commited, it must then be "pushed" into the cloud, i.e. Github, in order for it to be shared. That is done simply by using the `git push` command. Once that is done, any changes you made on your local repository, from this point refered to as a repo, will then be added to the repo in GitHub (the cloud) so that it can be accessed by other developers regardless of where they are. 
1. `git add`
2. `git commit`
3. `git push`

And that is the basic workflow between Git and GitHub.

#### Here are a few basic commands to get started with Git:
- `git status` a basic command that shows the current status of your repo and displays if there are any changes that need to be added, commited or any conflicts addressed. This command should be run often!
- `git clone` this command run preceeding a GitHub repo url will clone that repo from the cloud onto your local machine, allowing you to work on it seperate from the cloud based repo.
- `git add` this command will add changes made locally to the git version control system so that they can be comited to the repo.
- `git commit` running this command will "save as" any changes that have been added using `git add` to the repo. Adding a `-m` flag following the command will allow for a message to be added to the commit detailing what change was made.
- `git push` this command will take any changes that have been commited to the local repo and *push* them into the cloud, adding them to the GitHub based repo. This allows your changes to be seen by everyone working from the cloud based repo.
- `git fetch` if there were changes made to the GitHub repo that haven't yet been added to your own local repo, this command will check to see what they are and let you know on your local machine.
- `git pull` running this command will bring the changes made on GitHub and add them to your local repo, bringing your local version up to date with the origin master, or the original source of the repo that is located on GitHub in the cloud.

With these basic commands, you will be able to begin building upon your repo both locally and on Github. Any changes you make locally can be shared with the others on your project and likewise the changes they make can easily be accessed and added to your local repo. The best way to learn more is to just ***git*** started practicing! 
