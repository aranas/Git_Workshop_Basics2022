# Git & Github Basics

## Git and the cake metaphor
Git has its own terminology and in the beginning it can be a little overwhelming. The Git way of thinking in snapshots and trees with temporal history can be unintuitive when you are used to version1.doc and version2.doc being physical files in a folder.
But you don't need to be an expert in order to use Git. Using Git is like baking a cake. You don't need to know all chemical reactions going on between baking soda and whatnot in order to get a decent sponge cake as long as you follow the recipe. Similarly, following the basic order of Git commands will get you far quickly. So in this workshop, we will set you up with the basic recipe needed to start using Git and GitHub for version control. During the workshop you will also get some first hands-on experience with Git & GitHub. This is only a starting point! We will provide you with plenty of references and resources to continue learning.

## Workshop requirements
In order to get lots of hands-on experience during the workshop, you need to set up the tools we will be using in advance on your own device. Please make sure you have taken all the following steps __before__ the workshop and ask us for help on Slack or mail if you encounter issues.

* __Get familiar with the terminal__. You should be comfortable with commands like ``ls``, ``cd``, ``mkdir`` . If you have never touched the terminal, don't worry! [This](https://blog.balthazar-rouberol.com/discovering-the-terminal) friendly introduction should provide you with everything you need to know for a start.
* __Create a workshop folder__ Create a new folder called git_workshop2020 (``mkdir git_workshop2022``). Having the same base directory structure will make it easier for us to troubleshoot during the exercises.
* __Download Git__ [here](https://git-scm.com/download/). During installation you will be asked to specify a default text editor. Unless you are familiar with Vi/Vim we recommend using a text editor you are comfortable using (recommended: Notepad for Windows or atom for MacOS). Other than that you can install with the pre-selected options. Git usually comes pre-installed on MacOS, however it is a good idea to update to the most recent Git version.
* Once you are done installing/updating Git, open the Terminal app and check your Git version by typing ```git --version```
* __Make an account__ on [GitHub](https://github.com/) and __share your username__ via the [google form](https://forms.gle/9Ae4bGvQAv7cqws57), so I can add you as contributor to our Workshop GitHub repository.
* __Set your Git identity__. When you first install Git, you want to specify your identity for future collaborative work. You can specify your name and email by typing the following commands directly in your Git console (the one you downloaded above): ``git config --global user.name "your-name"`` and ``git config --global user.email "your-email"``.
* __Set up a personal access token__. When interacting with GitHub from your local machine you will need to go authenticate yourself.  There are multiple ways how to do it. One is to use a personal access token. A personal access token is basically a password but instead of setting it yourself, you have to generate it via the GitHub website. To save some time, please already generate and save your personal access token for later use during the workshop. [Here are the instructions of how to do it.](https://docs.github.com/en/enterprise-server@3.5/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

## Schedule
10:00  :wave: Welcome
10:15  :speaker: Intro Git version control + basic workflow
10:30  :computer: Exercise 1 - make your first local commit
10:50  :cookie: & Stretch
11:55  :speaker: GitHub & remotes
11:15  :computer: Exercise 2 - push your changes to remote
11:40  :mortar_board: Wrap-up
