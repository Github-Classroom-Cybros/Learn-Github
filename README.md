# Learn-Git-Github
A beginner's Git and GitHub tutorial 
`Source: Udacity & GitHub Guides`

---

## GitHub:

I’m keen not to overwhelm you, so I’ve made an annotated screenshot of a GitHub project, so that you can quickly become familiar with the most common features. Yes, GitHub is more than simply a project repository, but that’s where you’re likely going to spend most of your time on the site.

![github-repository-annotated](https://user-images.githubusercontent.com/25201562/31314300-36a8d96e-ac1b-11e7-8bca-027cae2f8f9e.png)

What you see is a project homepage. Across the top, in point one, are listed the project name, how many people are watching it, how many people have given it a vote of confidence by starring it, and how many people have forked it, perhaps to make changes of their own to it and contribute to it. Then, in point two, there’s the number of commits to the current branch, the number of branches, the number of releases, and the number of contributors. Next, in point three, there’s the branch picker, then below that there’s a listing of the top-level files in the project, and when the last commit was.
Over on the righthand side, in point four, you have the key navigation options. These are:

* __Code:__ The view you’re on by default, showing the files in the project.
* __Issues:__ A simple but effective issue tracker, whether you and the team want to report bugs and problems, make requests for new features, or other such tasks.
* __Wiki:__ A simple but effective wiki for documenting the project in more detail than a standard `README` file allows.
* __Pulse:__ A summary of statistics about the project, including open and closed issues. Here is where you find out how active the project is.
* __Graphs:__ A timeline of commits, followed by a breakdown of commits by individual contributor. You can then use the available tabs to look at the project activity in detail, based on a series of key metrics including code frequency, least to most active days for contributions, and so on.

Finally, also on the righthand side, there’s the link to the repository URL. If you want to clone this project, this is the URL you pass to `git clone`.

Now let’s look at the __commit__ history, by clicking commits. There you see the commits in reverse chronological order. On the left, you see the commit short description, the author’s username, and when the commit was made. On the right, the short version of the commit hash, and a link to the commit.
Click the commit hash, so you can see the changes it contains. In this example, we see a side-by-side diff of the project’s `README` file and a second file, `library/Zend/Version/Version.php`. You can see on the left what was removed from the previous version, and on the right what was added to this version. Above each commit, on the lefthand side, you see a short summary of the changes, which shows both the total changes (in this case 15) and a visual representation. Now here’s some fun.

![github-commit-changes-inline-comment](https://user-images.githubusercontent.com/25201562/31314339-2fe2913c-ac1c-11e7-8484-65106e3020ed.png)

Mouse over either the left or right sides. Notice a blue plus icon appears? If you click on it, you can comment on the code at that point in time. This is an excellent feature, as it makes GitHub a truly collaborative coding experience. One last thing, want to comment on the commit as a whole? There’s a comment box at the bottom of every commit. Click through the other tabs, and see what you find in each.

Note: Open source enthusiasts who are __familiar with How to create project and repository__ can skip the content below and learn more about [push and pull requests](https://guides.github.com/activities/hello-world/)

## Adding Project to GitHub

Now let’s get the simple project we’ve been working on into GitHub. To do that, after you’ve logged in to your account, click the plus symbol in the upper righthand corner, and click New repository from the dropdown. There you’ll see the new project creation form.

![github-create-new-repository](https://user-images.githubusercontent.com/25201562/31314370-bb31186c-ac1c-11e7-9c5a-6a1cb6cd78e0.png)

In the `Repository name` field, add a name. It needn’t be special: “first-project” works. Give it a description if you want. Perhaps “My first GitHub project.” Then, leave the project with the default of public. That way anyone can find it if they search for it. Finally, click the Initialize this `repository with a README` checkbox, and leave the two select boxes set to `None`. Now click `Create repository`.

![github-create-repository](https://user-images.githubusercontent.com/25201562/31314372-d47946d2-ac1c-11e7-9c8f-1b87c0a41038.png)

You’ll now be taken to the quick setup page. This page gives you a host of post-setup information about integrating your new GitHub project with your existing local repository, which we’ll do, or cloning it fresh. We’re going to add GitHub as a remote for our project. To do that, copy the first line under …`or push an existing repository from the command line`, and paste it in the terminal where you’ve been working up till now.

![github-post-repository-creation](https://user-images.githubusercontent.com/25201562/31314378-1de4bcde-ac1d-11e7-8f04-cfe609c3732a.png)

Doing so won’t display any output. Now copy the second line and paste it into your terminal. This will push our changes to GitHub. You’ll see output, something like that shown in the screenshot below. Now go back to GitHub in your browser and refresh the page. You’ll see our `README.md` and `index.php` displayed in the files list, and the contents of the README.md rendered at the bottom of the page.

![github-post-first-push](https://user-images.githubusercontent.com/25201562/31314387-4f2c67ba-ac1d-11e7-8c35-707c5d0c2e8f.png)


Now, Since you are __familiar with How to create project and repository__ learn more about [push and pull requests](https://guides.github.com/activities/hello-world/)

For more resources please visit:
  * [Interactive online tutorial](https://learngitbranching.js.org)
  * [GitHub Guides](https://guides.github.com/)
  * [Udacity Free Course](https://www.udacity.com/course/how-to-use-git-and-github--ud775/)
  * [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
  * [Github for Beginners](https://www.youtube.com/watch?v=3RjQznt-8kE&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)
  * [Git Tutorials - thenewboston](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGAKWClAD_iKpNC0bGHxGhcx)
  * [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)
  * [Slides from MIT SIPB Understanding Git Class](http://web.mit.edu/cluedumps/slides/understanding-git-2008.pdf)
  * [Try Git](https://try.github.io/levels/1/challenges/1)
  * [Code School](http://gitreal.codeschool.com/levels/1)
  * [CodeCademy](https://www.codecademy.com/learn/learn-git)
  * Installing Git
    * [Instructions for Windows](https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-windows-md)
    * [Instructions for Mac](https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-mac-md)
    * [Instructions for Linux](https://gist.github.com/derhuerst/1b15ff4652a867391f03#file-linux-md)

## The Bottom Line

And that’s the basics of how to work with Git and GitHub. I hope you’ve seen that, whilst there are quite a lot of concepts to take in, once you’ve gotten a handle on the basics, you can pick it up reasonably quick, with some patience.
There’s so much more to cover and there’s the opportunity to do so here. But one thing about both Git and GitHub—the community behind them is extremely supportive and generous in the sheer volume of information contributed. You’ll be in good hands.
