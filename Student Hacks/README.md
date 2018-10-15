## Upload what you learnt!

Even if you have been teaching yourself how to code in a new framework or making
a small script, you comment it and upload it here to show what you've done.

You do not have to necessarily talk about it, if you do comment it, you can mention
what you have done.

To upload, if you are not familiar with Git already, you can follow our previous presentations. This will make you familiar with how to contribute to other user's code on GitHub especially.


### How to upload?

In order for you to upload your content to the repository you can do the following:

**1.** Fork the repository from GitHub to your own account, by clicking "Fork" at the top right-hand side of this page!

**2.** Once it has been forked to your account, **git clone** your repository i.e. using the command line.
```bash
> git clone https://github.com/[Your Account Name]/PlymHack2018.git
```

**3.** Go ahead and open up the cloned repository folder which would be under a similar name as "PlymHack2018", inside it locate to the *"Student Hacks"* folder and in that folder **create a new folder under your name**, i.e. the directory will look like this:

```bash
> PlymHack2018
    > On The Day - Resources
    > Student Hacks
        > John Bloggs (this is your folder)
            > Project File 1
            > Project File 2
            > etc.
```

**4.** Copy and paste your project files which you have been working on today into your folder in the repository.

**5.** Go ahead and open up Git Bash (right click in a free space on the Git Bash folder on Windows and select open in git bash), then proceed to push to your copy of the PlymHack repository your files, you maybe asked to enter your GitHub credentials when pushing to your repository.

```bash
> git add --all
> git commit -m "Added John Bloggs Hack folder"
> git push origin master
```

**6.** After you have pushed, go back to GitHub and head over to your copy/fork of the PlymHack2018 repository and click on the **New pull request** button and on the following page click on green **Create pull request** button. You will be asked enter some basic information as to what the pull request contains, enter your title as the same one you used as the commit message i.e. "Add John Bloggs Hack folder" and enter a comment about what the project is about/or what you learnt today!

**7.** Just click on the bottom **Create pull request** and that's it, a new request as been created on the main PlymHack2018 repository and we will accept the request in!
