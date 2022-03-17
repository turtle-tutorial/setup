# Setup Tutorial

This tutorial just helps you setup a super basic website with Github pages.

# Tutorial

## Requirements
- A Github account
- VSCode
- Git (Windows)

## 🔨 Creating a repository
Create a new github repo, call it whatever you like! Whatever it gets called, it'll become part of the url path to your website.
So if you create a repo call "my-repo", and your username is "janesmith", your website url would be `janesmith.github.io/my-repo/`.

![Create repo](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/create_repo.png)

If you name the repo the domain name (`<your-username>.github.io`) then the website url will be what's written, without a path (the `/my-repo/` part) extending it.

## ⬇️ Clone the repo in VSCode
In Github, copy the git URL by clicking "Code" and then the clipboard button in the dropdown.

![Copy repo url](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/copy_repo_url.png)

Open VSCode and on the left panel, select the source control tab, and click clone repository.

![Clone repo in vscode](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/clone_repo.png)

Paste the URL you copied before into the available input and hit enter. Select where you want to save your repo project folder to, then open the newly cloned folder.

## 🎉 The fun part
Make a website! The important thing is to make sure that the root of your project contains an `index.html`.

## ⬆️ Uploading to Github
In the left panel of VSCode, select the source control tab. Here you can see all the files you've added and can chose, by clicking the `+` icon, which files you want to upload. Along with a message box, you can use to give some details about what code you've written.

![Commit changes](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/commit_changes.png)

Once your done writing your notes and selected the files you want to commit, press the tick. If you press the tick without selecting any files, you'll be given the option to commit all files. Congrats! You've made your first commit!

You should now have a "sync changes" button to push and upload your code to Github. If you still have files that you need to commit, but want to push first, you can select the push option from the dropdown.

![Sync changes](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/sync_changes.png)

## 📖 Publising to Github pages
In your github repo, you should now be able to see your code! But to get it onto an actual website, there's a few more steps we need to take.

Click on settings in the tab bar, then go to pages. Set the branch to `main` and the root directory to `/`. Click save and congrats! Github will upload your code to a server (which may take a minute or so) and publish it to a URL. You only have to do this once, so if you push more code to the repository, Github will automatically upload the latest version to the website.

![Publish pages](https://raw.githubusercontent.com/turtrl/setup/main/docs/img/activate_pages.png)

You can see the example site I made here by click the url to the right of the repo files or [here](https://turtrl.github.io/setup/).