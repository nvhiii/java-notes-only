# java-notes-only

##Table Of Contents
Readme Tips & Tricks: [Github Docs](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Java [Notes](Notes.txt) <!-- I am just testing out github repo such as relative links, etc. -->

Repo [Cloning](https://github.com/nvhiii/java-notes-only/blob/main/README.md#how-do-i-add-this-github-repository-to-my-pc1)

Repo [Committing & Pushing](https://github.com/nvhiii/java-notes-only/blob/main/README.md#how-can-i-commit-and-push-to-this-repository3)

## How do I add this Github repository to my pc?[^1]
*Part 1*

1. Copy the repo first (top right corner there is a green button labelled "Code". Click on that button and then select the HTTPS clone link

2. Press Windows + r key on your keyboard to open the run interface and enter the word "cmd" and press enter to get the command prompt

   - *You will then see a line similar to this in the command prompt:*

```
C:\Users\User>

// "User" will be the name of the username you are logged in under
```

4. After getting the above prompt on your command prompt, please change directory to Desktop, as that is where the JAVA-Testing file will be saved by default!
   - *To change the directory to your desktop, enter the following after the step 2 codeblock*

```
cd Desktop

//this 'cd' changes directory to Desktop resulting in:

C:\Users\User\Desktop>
```

5. If you followed all steps, including the mandatory prerequisite, you should already have git installed on your pc. It not, please fulfill the ***mandatory prerequisite*** before proceeding!
   - *Now you can simply enter the following into the terminal to clone a repository*

```
git clone (link)
```

   - (link) should be copied from step 1[^2]

6. When all is said and done, the command prompt should take a few seconds to a minute to clone the repo in your Desktop, so you can access all the notes and code from this repo!

## How Can I Commit and Push to this Repository?[^3]
*Part 2*

***PREREQUISITES:***
- Must have already cloned the repo onto your machine
- Must have REPOSITORY ACCESS

1. After fulfilling the prerequisites, you must change directory into the directory of the Github repo. For this example, I am assuming that the cloned repo is in the Desktop as per part 1.
   - Open the terminal using the Windows-Key + r and entering "cmd" without the quotations and then press enter
   - You should have a terminal with the following:

```
C:\Users\User>

// if you don't have this, fret not. Just enter the following after whatever you see on your screen:

cd /

cd C:

cd Users

cd User
```

2. After getting the appropriate prompt in the command prompt, change directory into the desktop or wherever the repo is cloned.

```
cd Desktop

// results in:

C:\Users\User\Desktop>
```

3. Then, change directory directly into the repository name

```
cd java-notes-only

// results in:

C:\Users\User\Desktop\java-notes-only>
```

4. In order to stage changes to the repo, you must first have the most current version of the repo.
   - To check for this enter the following into the terminal:


```
git status

// this will show if you have unstaged changes or if your branch is up-to date with the repo on github
// if your repo is not up-to-date, you must first pull all changes using git pull
```

5. Then after the status check of if you have an up-to-date repo with Github, enter the following into the terminal

```
git add .

// this adds all changes in all files of the repo
// this step is called staging your changes
```

6. Finally, you must push your staged changes to Github
   - *Enter the following in your terminal to push staged changes to Github*

```
git push

// Wait about 30-60 seconds to see a bunch of text on your terminal which shows what you added to the repo and will say when the changes are staged in main-->main
```

7. To double-check, you can go on github and you should see the repo now updated!

> Cheers - Nahi! :shipit:

## Progress
- [ ] Finished the Readme
- [ ] Finished all the Notes
- [ ] Tutorial optimization for Linux
- [ ] Tutorial optimization for macOS

## Honorable Contributor(s):
@asror1

[^1]: Please keep in mind this tutorial is based on the Windows OS as of right-now
[^2]: The link should be the copied HTTPS link
[^3]: Once again, please keep in mind this tutorial is based on the Windows OS as of right-now
