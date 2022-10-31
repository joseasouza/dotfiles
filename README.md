# dotfiles

1. Clone this repository in your home folder:
````
git clone git@github.com:joseasouza/dotfiles.git ~/dotfiles
````
2. Run the install script:
````
~/dotfiles/install
````

### VS-Code dev container setup

1. In settings.json, add:

````
    "dotfiles.repository": "joseasouza/dotfiles",
    "dotfiles.targetPath": "~/dotfiles",
    "dotfiles.installCommand": "~/dotfiles/install",
````

### Note
Your environment or dev container should have the zsh package installed
