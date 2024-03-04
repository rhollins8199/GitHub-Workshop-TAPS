# START HERE

✨ Welcome to TAPS Club Git & GitHub Essentials Workshop! ✨ 

This workshop is broken up into 6 parts:

- **[Part One:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#computer-part-one-install--configure-git)** Install & Configure Git :computer:
- **[Part Two:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#fork_and_knife-part-two-fork--clone-repo)** Fork & Clone Repo :fork_and_knife:
- **[Part Three:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#cactus-part-three-manage-branches)** Manage Branches :cactus:
- **[Part Four:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#-part-four-update--manage-files)** Update & Commit Files 📝 
- **[Part Five:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#-part-five-sync-forked-repo)** Push Changes to Forked Repo 🔄
- **[Part Six:](https://github.com/rhollins8199/TAPS_GitHub_Workshop?tab=readme-ov-file#-part-six-merge-updates-into-repo--create-pull-request)** Merge Branches & Create Pull Request to Workshop Repo🤝

*Note: Additional Git resources are available within the PowerPoint folder. Download the PDF version of the PPT to access the links.*

<!-------------------------------------------------------------------------------- Part One -------------------------------------------------------------------------------->

## :computer: Part One: Install & Configure Git

<strong>1.</strong> Download Git onto your personal computer.
```
https://git-scm.com/downloads
```
<strong>2.</strong> Open Git Bash terminal.

- **Windows:** Search `git bash` in the Start menu.
- **Mac:** Open terminal and type `git bash`.
- **Linux:** Open terminal emulator and type `git bash`.
  
<strong>3.</strong> To ensure that you have Git installed enter the following commands: (You should see something like "*git version 2.40.0*")
```
git --version
```
<strong>4.</strong> Close and re-open Git Bash.

<strong>5.</strong> Configure user information used across all local repositories.
```
git config --global user.name [firstname lastname]
```
```
git config --global user.email [github email]
```
```
git config --list 'C:/Program Files/Notepad++/notepad++.exe'
```
<strong>6.</strong> Check to see if information updated successfully.
```
git config --list
```

<!-------------------------------------------------------------------------------- Part Two -------------------------------------------------------------------------------->

## :fork_and_knife: Part Two: Fork & Clone Repo

<strong>1.</strong> Fork the Workshop repo into your personal remote repository. ⤵️

> *Note: This makes a copy of the Workshop repository into your own remote repository within GitHub.*

![image](https://github.com/rhollins8199/TAPS_GitHub_Workshop/assets/103677691/e60bcbc7-29cc-49a7-a37e-6ec126fb4a15) <!-- Replace when Finished -->

- Rename your forked repository `TAPS_GitHub_Workshop_[YourName]`.
- Copy the `main` branch only

<strong>2.</strong> Create a new folder in a location you can easily access/remember (e.g Desktop). 

- Name it `Workshop_Demo`.
- Right click on the folder, click `Show more options`, then `Git Bash Here`.
  
<strong>3.</strong> Go to your forked repo and copy the HTTPS link. ⤵️

![image](https://github.com/rhollins8199/TAPS_GitHub_Workshop/assets/103677691/7784d151-d24a-4b75-9bf8-2e203e4e2386)

<strong>4.</strong> In your Git Bash terminal, make sure you are in your `Workshop_Demo` folder and clone your remote repo into the folder.

> *Note: This makes a copy of the your forked repository into your own local repository within your personal computer.*

```
git clone [url]
```
<strong>5.</strong> Change folder directory to be in correct folder location.
```
cd TAPS_GitHub_Workshop_[YourName]
```

<!-------------------------------------------------------------------------------- Part Three -------------------------------------------------------------------------------->

## :cactus: Part Three: Manage Branches

<strong>1.</strong> You should currently be in the main branch, but we are about to create a new branch.
```
git branch [YourFirstName]
```
<strong>2.</strong> Switch to new branch.
```
git checkout [YourFirstName]
```



## 📝 Part Four: Update & Commit Files
## 🔄 Part Five: Push Changes to Forked Repo
## 🤝 Part Six: Merge Branches & Create Pull Request to Workshop Repo
