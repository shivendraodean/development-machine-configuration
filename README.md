# Guide to Development Machine Set-up

### Install Oh My Zsh
https://ohmyz.sh/

```
    sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```


### Installing Package Manager - Homebrew 
https://brew.sh/
```
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```


### Install packages
- Copy Brewfile to `/Users/{username}`
- Run `brew bundle`

### VS Code Config

Run VS Code from the terminal by typing 'code' after adding it to the path:

- Launch VS Code.
- Open the Command Palette (⇧⌘P)
- Type 'shell command' to find the *Shell Command: Install 'code' command in PATH command.*
- Restart the terminal for the new $PATH value to take effect.
