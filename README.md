# Git Commands

1.Create a folder called learn_git.

![mkdir](./Screenshots/Screenshot%201.png)

2.Cd (change directory) into the learn_git folder.

![cd](./Screenshots/Screenshot%202.png) 3. Create a file called third.txt.
![touch](./Screenshots/Screenshot%203.png) 4. Initialize an empty git repository.
![git init](./Screenshots/Screenshot%204.png) 5. Add third.txt to the staging area.
![git add](./Screenshots/Screenshot%205.png) 6. Commit with the message "adding third.txt".
![git commit -m](./Screenshots/Screenshot%206.png) 7. Check out your commit with git log.
![git log](./Screenshots/Screenshot%207.png) 8. Create another file called fourth.txt.
![touch](./Screenshots/Screenshot%208.png) 9. Add fourth.txt to the staging area.
![git add](./Screenshots/Screenshot%209.png) 10. Commit with the message "adding fourth.txt"
![git commit](./Screenshots/Screenshot%2010.png) 11. Remove the third.txt file.
![git rm --cached](./Screenshots/Screenshot%2011.png) 12. Add this change to the staging area. (Using the command "git add . "
![git add](./Screenshots/Screenshot%2012.png) 13. Commit with the message "removing third.txt".
![git commit](./Screenshots/Screenshot%2013.png) 14. Check out your commits using git log.
![git log](./Screenshots/Screenshot%2014.png) 15. Write the appropriate command to list all the global configurations for git on your machine.
![git --global --list](./Screenshots/Screenshot%2015.png) 16. You can type git config --global to find out how to do this.
![git --global](./Screenshots/Screenshot%2016.png)
17.Change your global settings to core.pager=cat
![git --global core.pager 'cat'](./Screenshots/Screenshot%2017.png)
