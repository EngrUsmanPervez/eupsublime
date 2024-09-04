# eupsublime

##### Installation
```
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/sublimehq-archive.gpg > /dev/null
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

sudo apt-get update
sudo apt-get install apt-transport-https
sudo apt-get install sublime-text
sudo apt-get install clang-format
```

### Configurations
```
Menu -> Preferences -> Settings
On the RightPanel, add this line
  "hot_exit": "disabled",
  "translate_tabs_to_spaces": true,
```
```
Spaces: 2
CTRL+SHIFT+P -> Clang Format -> Set Style -> Mozilla
```

```
# Auto format
Go to Menu => Preferences => Package Settings => Clang Format => Settings-User
{
  "style": "Mozilla",
  "format_on_save": true,
}
```

```
CTRL+SHIFT+P -> Install Theme
This will load all color schemes

Project Implemented on [Academic Master](https://academic-master.com/)

```

Project designed and Implemented for [Academic Master](https://academic-master.com/)

