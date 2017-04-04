# This is a simple tool for translating from any into any language.
It uses Google translator for translation. 

### Installation

```sh
$ sudo apt install [xsel](https://apps.ubuntu.com/cat/applications/xsel/)
$ chmod -v 755 ez-trnslt
$ sudo mv ez-trnslt /usr/bin/
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
