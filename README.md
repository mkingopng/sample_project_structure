# sample_project_structure

Note: most of these things can be done from the command line. I feel like the 
really good programers i meet can do it from the command line. I cannot but 
should learn. I just use the features in PyCharm to do this. VS Code as the same features

Steps to create a new project
- create a new project
- add a licence. Apache, GNU or MIT is fine
- create a .gitingore file this excludes the files and directories that you don't want to be tracked by git
- add .idea to the .gitignore file if you use pycharm, add .vscode if you use visual studio code
- add /data/ to the .gitignore file
- add a README.md file
- create an interpreter & package manager for the project, i use poetry but the standard is pip
- install your dependencies using your chosen package manager
- create a src directory. Or name it something more meaningful if you like. This is where a lot of your code will live
- create a data directory
- create a tests directory
- create a git repository and push your first commit.
- get started

If you use poetry, add the pyproject.toml file to the project but add the 
poetry.lock fiule to gitignore

if you use pip, add the requirements.txt file to the project but add the .venv 
directory to the .gitignore

I usually only have the main file in the project root. I create a data file 
which is part of the .gitignore so that it doesn't make the project too huge.
I use src as the main code directory. I try to break my code up into 
smaller files and put them in the src directory. 

I use pytest to write test for my code. I try to write the tests as i'm 
going but i kow i need to do a lot better. There are other testing 
frameworks but pytest is pretty modern and comprehensive.

Often i will have a directory for research. In theory i should have a 
directory for documentation but honestly i never do. Mainly because i dont' 
get to collaborate much i think. I just use docstrings and comments as 
documentation

Commit & Push once you've made little progress and a change you want to keep. 
I do it as often as i can remember, which is probably not enough. I went 
through a period where I'd commit too often. Its hard to find a sweet spot.

good commit messages are important. I think maybe if i can't write a good 
commit message then i don't need to commit and push. 

Commit is where you create a local checkpoint of your work. Push is where you
push those changes to GitHub. Locally you can roll back to any commit. But 
your collaborators can only access the code from GitHub after you've pushed.

There are a lot of things to cover about forking, merging, pull requests, 
code reviews, etc etc etc but i think this is a good start. Plus i'm not 
great at that stuff so i can't teach it very well yet! I think you need 
these skills a lot more when you work in a team.

There is a whole other discussion when you want to deploy your code to 
cloud, eg AWS.