# ~$/zsh-prompt

![](https://image.ibb.co/gVnoCz/Screen_Shot_2018_08_31_at_09_29_44.png)

* [Cheatsheet](http://nerdfonts.com/#cheat-sheet)
* [Colors](https://jonasjacek.github.io/colors/)
* [Configs](https://github.com/bhilburn/powerlevel9k/wiki/Show-Off-Your-Config)
* [Tutorial](https://medium.freecodecamp.org/how-you-can-style-your-terminal-like-medium-freecodecamp-or-any-way-you-want-f499234d48bc)

## Setup

```bash
cd zsh-prompt
brew cask install iterm2
brew install zsh
sudo gem install colorls
chsh -s /bin/zsh
```

*Change BASH_PROFILE_HOME path to your cloned repo*

```bash
cp bash/home_bash_profile ~/.bash_profile
cp zsh/home_zprofile ~/.zprofile
cp customization/fonts/* ~/Library/Fonts/.
```

## iTerm2

```
iTerm2 -> Preferences -> Profiles -> Text -> Font -> Change Font
```
Select the font ```Meslo LG L DZ Regular Nerd Font Complete``` and adjust the size if your want too. Also check the box for Use a different font for non-ASCII text and select the font again. It should be displaying the new font and icons in the prompt.

```
iTerm2 -> Preferences -> Profiles -> Colors
```
Import ```material-design-colors.itermcolors``` file and select it from the list.


To configure iTerm2 Floating mode:

![](https://image.ibb.co/jNbqze/Screen_Shot_2018_09_03_at_12_30_50.png)
![](https://image.ibb.co/dDXVze/Screen_Shot_2018_09_03_at_12_30_40.png)
![](https://image.ibb.co/jBMXvK/Screen_Shot_2018_09_03_at_12_36_28.png)

## Customization

* bash/custom_bash_profile: Add aliases, functions, etc.
* zsh/custom_zsh_profile: Change prompt colors, plugins, etc.
