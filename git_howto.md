## ***HOW TO CLONE LEGACY TZ GITHUB***
1. Get added to the repository.
2. Download and install Git for Windows. https://git-scm.com/download/win (make sure `Windows Explorer integration` is checked on the installer. Everything else can be left to default.)
3. Once Git is installed, right click where you'll want to have your Legacy TZ files.
4. Select `Git Bash here`.
5. Type `git clone https://github.com/truezetsu/legacy-tz`. It will then prompt you for your GitHub credentials.
6. After typing your GitHub credentials, a folder named `legacy-tz` will be created wherever you opened Git Bash from. Legacy TZ will then be downloaded, and the folder will be configured to work with that Git repository.



## ***HOW TO GET UPDATES FROM LEGACY TZ GITHUB***

**This should _always_ be done before working on the build or pushing anything new.**
1. Open a Git Bash window in your `legacy-tz` folder by right clicking the folder and selecting `Git Bash here`.
2. Type `git pull`.
New files will be automatically added/updated.



## ***HOW TO ADD TO THE LEGACY TZ GITHUB***
1. Once you've added your new mod files, open a Git Bash window in your `legacy-tz` folder by right clicking the folder and selecting `Git Bash here`.
2. Type `git add *`. This will add all files not already in the GitHub repository.
3. Type `git commit -m "commit message here"`, and replace `commit message here` with something meaningful, to denote your changes.
4. Type `git push`. This will upload your changes to the repository.
