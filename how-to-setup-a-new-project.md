# How to setup a new project

1. Go to your projects folder

2. Create a new folder using "`mkdir your-projects-name`"

3. Switch to the new folder using "`cd your-projects-name`"

4. Initialize git with "`git init`"

5. Initialize npm with "`npm init`"

6. Add file _.gitignore_ with "`touch .gitignore`"

7. Open _.gitignore_ with "`code .gitignore`" in Visual Studio Code (Or use vim if you are keen enough)

8. Add "`.DS_Store`" and "`node_modules`" to the file. Then save and exit.

9. Add file _README.md_ with "`touch README.md`"

10. Open _README.md_ with "`code README.md`" in Visual Studio Code (Or use vim if you are keen enough)

11. Add relevant Information to _README.md_. Then save and exit.

> You can also do 6. to 11. directly in Visual Studio Code by opening it with "`code .`" and add both files and their relevant content there.

12. Install vite with "`npm install vite`"

13. Open _package.json_ with "`code package.json`" in Visual Studio Code (Or ..., you know the drill)

14. Add "`"dev": "vite",`" under "`scripts`"

15. Add prettier with "`addprettier`"

16. Add all files in your local repository with "`git add .`" to stage them for the initial commit.

17. Use "`git commit -m "Initial Commit`" to commit the staged files

18. Create a new repository on GitHub: https://github.com/new

19. Give your repository a name (usually the same as your local repository)

20. Set to public if you want others to be able to review it, otherwise set to privat

21. Initialize it without anything else

22. Choose _…or push an existing repository from the command line_

23. Go back to the terminal and use the following commands:

    - `git remote add origin git@github.com:USERNAME/REPONAME.git`
    - `git branch -M main`
    - `git push -u origin main`

24. Congratulations, you are all set up.

25. Create a new branch with "`git checkout -b name-of-your-branch`"

26. This will create a new branch and directly switch to it

27. Start your project with "`npm run dev`"

28. Start coding your project in Visual Studio Code with "`code .`"

# Happy hacking!

[Back](README.md)
