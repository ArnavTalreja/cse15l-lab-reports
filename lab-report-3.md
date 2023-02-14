# RESEARCHING COMMANDS
In this lab report, I will be exploring command-line options for the `find` command. I will be using a cloned copy of the skill-demo1-data repository to demonstrate the commands.
### SEARCHING FOR FILES BY TYPE:-
The `-type` modifier of the `find` command allows us to search for files within a directory by the type of file.\
For example, `find * -type d` command prints all the individual directories within the repository.
![Image](1.jpg)
This command can be really helpful when we do not have file explorer or finder to be able to navigate through the files and we do not know how many nested directories/folders there are.\
Another example would be using `find * -type f` command prints all the files in all the directories of the skill-demo1-data repository.
![Image](2.jpg)
This command can be helpful in situations when we are trying to determine the number of files in the entire repository. We did the same thing in lab. But we had to use the `find` command, followed by the `grep` command, which was then followed by the `wc` command. This was because the `find written_2/` command we used in lab not only printed out the files but also printed out the name of the folders, which gave us an inaccurate number of lines. Hence, we had to use `grep`. But if we observe closely, `find * -type f` command only prints out the files, thus solving the problem.
