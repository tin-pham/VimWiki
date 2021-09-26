### Git Config

* Global (System): /etc/gitconfig 
	 - `git config --system`

* Global (User): ~/.gitconfig || ~/.config/git/config
     - `git config --global`

* Local: .git/config
     - `git config --local  (Default)`
	 
	 
	 
#### Setup Identity
```shell
git config --global user.name "YourName"
git config --global user.email youremail@example.com
```

#### Editor
```shell
git config --global core.editor vim
```

#### Default Branch Name
```shell
git config --global init.defaultBranch master
```

#### Checking Setup
* Get all 
```shell
git config --list
```
* Get specific
```shell
git config user.name
``` 

##### Getting Help
```shell
git help <command>
git <command> --help
man git-<command>
```
