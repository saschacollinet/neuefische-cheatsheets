# How to setup a new react app

1. Go to your projects folder

2. Create a new react app with "`npx create-react-app your-apps-name`"

3. This will automatically create a new folder for your app. Switch to it with "`cd your-apps-name`"

4. Install react router with "`npm install react-router-dom`"

5. Install styled components with "`npm install --save styled-components`"

6. Add prettier with "`addprettier`"

7. Add all files in your local repository with "`git add .`" to stage them for the initial commit

8. Use "`git commit -m "Initial Commit"`" to commit the staged files

9. Create a new repository on GitHub: https://github.com/new

10. Give your repository a name (usually the same as your local repository)

11. Set to public if you want others to be able to review it, otherwise set to privat

12. Initialize it without anything else

13. On the next page choose _…or push an existing repository from the command line_

14. Go back to the terminal and use the following commands:

    - `git remote add origin git@github.com:USERNAME/REPONAME.git`
    - `git branch -M main`
    - `git push -u origin main`

These are also shown in the box on GitHub. Make sure you choose SSH if you copy them out of the box

15. Congratulations, you are all set up!

16. Switch back to the terminal and create a new branch with "`git checkout -b name-of-your-branch`". This will create a new branch and directly switch to it

17. Start your app with "`npm start`" This will start the dev server locally. By default it will start at http://localhost:3000/ and automatically open in your default browser

18. Back in the terminal, start coding your app in Visual Studio Code with "`code .`"

# Happy hacking!

[Back](README.md)
