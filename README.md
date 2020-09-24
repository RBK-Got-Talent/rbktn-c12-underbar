## Underbar part one

### Before you start

Fork this repo to your personal github page. Clone the repo down to your machine.

You will be working on this sprint with your partner so be sure to add a remote by using the `git remote` command.

For example, let's say Matt is pairing with Yousef.
Matt and Yousef are working on one machine. How do Matt and Yousef each commit to their github account from one machine?

Before starting any work on the sprint:

1. Matt forks the repo and clones the repo to the machine
2. From the command line Matt types `git remote add yousef <repo url>`

Now Matt and Yousef begin working on the sprint. They get some work done and want to commit and push to github:

3. Type `git status` -- this will show you which files have been changed since the last commit
4. Type `git add .` -- this will add any files changed since the last commit
5. Type `git commit -m <your commit message>` -- be sure and give a descriptive commit message
6. Type `git push origin master` -- this will push to Matt's repo
7. Type `git push yousef master` -- this will push to Yousef's repo

### Bare minimum requirements:

Be sure to follow good pairing practices. -- Navigator explains his thinking to the driver. The driver listens to the navigator and implements what the navigator says in the code.

Open the `SpecRunner.html` in the browser to view the tests.
Open the `underbar.js` file in Sublime Text.

Try and work through as many of the problems as you can with your pair.
When you want to test your code, refresh `SpecRunner.html` in your browser.
