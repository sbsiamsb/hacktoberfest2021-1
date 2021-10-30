![HacktoberFestBanner](../../blob/main/_src/banner-dark.png)

Hi Students Of Delhi Technical Campus , This is October.

And you guys are saying "So, What?"

THIS IS HACKTOBER FEST 2021. YES, the event of FREE swag.
A full-month event is started. Wohooo.

(Submit 4 PR and Get a Tee from HacktoberFest 2021, *not from us.* )

### Rules

 - Fix any issues which is inside the [Issues tab.](https://github.com/cestaSociety/hacktoberfest2021/issues)
 - Didn't find any issues? [Create one](https://github.com/cestaSociety/hacktoberfest2021/issues/new) and then submit a PR.
 - You have to submit 4 PRs to be qualified for the swag.

### How to start

*Prerequisites - A github account.*

 - Go to https://hacktoberfest.digitalocean.com/ 
 - Tap on "Start Hacking"
 - Sign up with GitHub. (GitLab not supported here)
 - Fill about you. and go ahead.
 - Complete all the Steps. Good to go
 - Now submit 4 PR here in this repo. That's all.

### How to submit PR?

Google It!
But why don't you tell us, simply here?
Googling is a very demanding skill to have in programming world. If you don't re-search when building any app/website then technically you are not following the code-of-conduct or your are OQ (over-qualified).

Still If you wanna know. [GitHub Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). After reading this, There is further reading in the same link everything is documented.

#### Help
- [How to pull request [Overview]](https://youtu.be/DIj2q02gvKs)
- [Merge Conflict / Comment](https://youtu.be/zOx5PJTY8CI)

### How to start contribution

How to do it?
 - Fork the repo. (Button on top right)
 - Clone your *FORKED* repo. (Not this repo)
 ```bash
 git clone git@github.com:<username>/hacktoberfest2021.git
 # Using ssh
 git clone https://github.com/<username>/hacktoberfest2021.git
 # Using HTTPS
 ```
 - Fix this code.
 - Commit it.
 ```bash
 git add . && git commit -m "I fix the code"

 # change "I fix the code" to explain what you did in brief.
 ```
 -  Push the code in your repositor
 ```bash
 git push origin main
 ```
 - Now create a PR from anywhere to [this](https://github.com/cestaSociety/hacktoberfest2021) repo.
 - Have a coffee and wait till it merges.

 -------------------------

 ### Additional help
 When working there are fellow developer who are also trying to fix other issue. Which makes ***your*** source stale. To fix it you need to get the fresh source. So how to do it.

#### Avoid Conflicts (Syncing your fork) 

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.

```terminal
git remote add upstream https://github.com/cestaSociety/hacktoberfest2021
```
 You can verify that the new remote has been added by typing:

```terminal
git remote -v
```

To pull any new changes from your parent repo simply run:

```terminal
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.

For more information on syncing forks [read this article from GitHub](https://help.github.com/articles/syncing-a-fork/).

-------------------------

![HacktoberFestBanner](../../blob/main/_src/footer-dark.png)
