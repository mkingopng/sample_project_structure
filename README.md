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

