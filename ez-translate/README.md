# This is a simple tool for translating from any into any language.
It uses Google translator for translation. 

### Installation
[Xsel](https://github.com/kfish/xsel) is a command-line program for getting and setting the contents of the X selection.
```sh
$ sudo apt install xsel
$ chmod -v 755 ez-trnslt
$ mv ez-trnslt /usr/local/bin/
```
Go to System settings -> Keyboard -> Key Combinations -> Additional

Click + 

Name - Any

Command - ez-trnslt

Apply

And create accelerator, for example Super+Q

Done!

### Setting
To set the desired language for translation, open the script and replace the ANY with your language.
> ...&sl=auto&tl=ANY&dt... 

For example translating into Russian 

> ...&sl=auto&tl=ru&dt...
