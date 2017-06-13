# Columbia InterVarsity Website

The point of truth for http://columbiaivcf.org/. Onboarding details follow:

## Links
Here are a few key links:

* [Columbia InterVarsity website](http://columbiaivcf.org/)
* [Github repo](https://github.com/imkevinchu/ivtech)
* [Bluehost hosting](https://my.bluehost.com/web-hosting/cplogin)

## Getting Started
Once you're set up on Git, please clone the ivtech repo to your own computer. The clone URL is right on the repo under "Clone or download." Now you should be able to edit the directory yourself and the code using whatever text editor of your choice.

## Pushing to Github
Once you've made and saved any changes to your local copy of the directory, pushing back to Github looks like this in the command line:

```
cd ivtech
git init
git status (Shows you if anything's changed since the last commit if you aren't sure)
git add . (Adds all changes to the commit)
git commit -m "[Commit description]"
git push origin master
```

The repo contains examples of language used in commit descriptions. It's good practice to include a description for every commit (even minor ones) rather than leaving it blank. Another best practice is to have your commit descriptions in present tense (like a revision history in case of rollback) e.g. "Add parallax scrolling, subsections according to spec (major commit)"

## Uploading to Bluehost
Github's purpose is for keeping a copy of the codebase, but Bluehost is where the actual website online lives.

* Download an FTP manager such as [Cyberduck](https://cyberduck.io/)
* Login to Bluehost
* Create a new FTP account for yourself in cPanel (under "FTP" at the top)
* Login to the website FTP server from Cyberduck
* Now you should be able to see the directory on the server—it's as simple as drag and dropping your local copy and replacing the older copy on the server

There you go! Any changes made will be reflected almost immediately online.
