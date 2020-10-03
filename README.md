# GIT COMMANDS

 > Installation Linux
``` bash
sudo apt-get install git 	#Debian/Ubuntu
sudo yum install git 		#Fedora
sudo pacman -S git 			#Arch
```

> Configrations
``` bash
git config --global user.name "YOUR NAME"
git config --global user.email "GITHUB EMAIL"
git config --global core.editor "YOUR FAV EDITOR"
```

> Commands 
```bash
[]git clone <url>		#download the whole repo to your local storage.
git status			#shows the status of each file in the repo (untracked, stagged, committed).
git add <file name | wild card>		#add a file to the stagged area.
git commit -m "commit message, details about the changes you made and why you made them"	#add the files in the stagged area to a commit, give the commit an id, and store the commit.
git log		#shows all the commmits made on this repo.
git show <commit id>	#shows the changes happened in this commit.

git push -u origin master	#push all the commits to the online repo on git hub.

```