# Intro to GitHub

GitHub is where all of the code for our robot will be stored.
You should have created GitHub accounts by now.
Send your **username** into the Discord **programming** channel.

## Branches

We seperate different versions of code that are actively being worked on using **branches**.
**Create a new branch and label it YOUR NAME**.
> [!TIP]
> Remember, Google is a programmer's best friend, if you have an issue, **Google it**. Try to avoid using ChatGPT for simple things or solving problems for you.

## Commits

Now that you are in your new branch, lets talk about **commits**.
Commits are like little snapshots in the code's history.
When you make a change in your code and commit it, it will be pushed to GitHub and it will be added to the history of changes. You can at any time revert your code 
to one of these previos snapshots or look at older versions of your code. We will also be using commits to hold each other accountable for changes made to the code.
Whenever you make a commit, **remember to be signed into your account**.

In the GitHub page, there should be a button called "New File", click on that and name the file "about.md". **Make sure you are in your branch that has your name, not the main branch.**
In the future I will show you how to use GitHub with VS Code.

In the **about.md** file, write the following:
[YOUR NAME]
My favorite food is [YOUR FAVORITE FOOD].

Once you have done that, commit your changes.

## Pull Requests

One you have finished your bit of code and tested it on the robot, we want to integrate it with the rest of the code. We can do this by creating a **pull request**.

On GitHub, go the **Pull Requests** tab
1. Click on **New Pull Request**.
2. For **base**, choose **main**
3. For **compare**, choose the branch with your name
If you had correctly commited your **about.md** file you should be able to create the pull request into the **main branch**.
