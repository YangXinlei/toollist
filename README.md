# toollist

0. [oh my zsh](https://ohmyz.sh/#install)

1. [scmpuff](https://mroth.github.io/scmpuff/) (git command enhance)
2. [outline](https://github.com/Jigsaw-Code/outline-client/) 密钥公式 ss://base64(method:passwod)@server-address:port [参考](http://howboring.us/archives/outline-accesskey-compatiblie-all-server.html)
3. [Maccy](https://github.com/p0deje/Maccy)  (clipboard manager, 替代alfred的剪切板管理，alfred免费版本就基本够用了)
4. 
```
git config --global alias.slog "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative"
```

5. [cleaner-for-xcode](https://apps.apple.com/cn/app/cleaner-for-xcode/id1296084683?mt=12)

6. [snap](https://apps.apple.com/cn/app/snap/id418073146?mt=12)

7. [show timestamp for each command line](https://stackoverflow.com/a/60842361)
```
#file .zshrc
RPROMPT=$PROMPT'[%D{%f/%m/%y} | %D{%L:%M:%S}]'
```

or using [oh-my-posh](https://pawelcislo.com/2021/11/14/my-vs-code-playground/)


8. Associating text editors with Git
```
git config --global core.editor "code --wait"
```

9. set calendar to light mode
```
defaults write com.apple.iCal NSRequiresAquaSystemAppearance -bool yes
```
