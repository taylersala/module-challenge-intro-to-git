## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
- Git is one of the most widely used version control systems.
2. What is the difference between Git and GitHub?
- Git is the version control system where you track it at the source while GitHub is a cloud based service that you can mange those repositories. Similar to having a bunch of videos personally, and posting them to youtube. 
3. Why do we create a branch?
- We create a branch to make our lives easier if multiple people are working on a project at the same time. It allows people to work simultaneously without real time overlap creatiing chaos. In addition it allows for better version control, and is great for peer review as multiple people must approve a branch before it is allowed to be merged. Having these branches is also helpful incase an issue arrises that was already fixed, it is easy to access the original code and paste it in incase it was written over in a later version.
4. What is the purpose of a Pull Request?
- A pull request allows you to see the changes that were made on your branch and compare them. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
- git checkout
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
- git fetch shows the branches and changes made to remote repositories without actually making those changes. git merge merges two or more existing branches, essentially taking two versions and updating them so order matters here depending on what branch you want to merge into. git pull downloads stuff from the remote repository and updates it to the local one.
7. What is a merge conflict?
-W hen two people have made changes to the same code on different branches and attempt to merge them. It conflicts and doesn't know which to prioritize. 
8. How do you resolve a merge conflict?
- Do a pull request check the differences make the neccesary changes in the code and update the other version not used to match the one you've deemed is the most effiecnt or correct option.