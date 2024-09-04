# eupsublime

##### Installation

```bash
wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/sublimehq-archive.gpg > /dev/null
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

sudo apt-get update
sudo apt-get install apt-transport-https
sudo apt-get install sublime-text
sudo apt-get install clang-format
```

##### Hot Exit

```bash
Menu -> Preferences -> Settings
On the RightPanel, add this line
  "hot_exit": "disabled",
  "translate_tabs_to_spaces": true,
```
##### Clang-Format Style

```bash
Spaces: 2
CTRL+SHIFT+P -> Clang Format -> Set Style -> Mozilla
```

##### Clang-Format Auto Format

```bash
# Auto format
Go to Menu => Preferences => Package Settings => Clang Format => Settings-User
{
  "style": "Mozilla",
  "format_on_save": true,
}
```

##### Clang-Format Auto Format Folder

```bash
find . -type f \( -name "*.c" -o -name "*.h" \) -print0 | xargs -0 clang-format -style=Mozilla -i
```

##### Load Color Schemes

```bash
CTRL+SHIFT+P -> Install Theme
This will load all color schemes
```

##### Academic Master

Project Implemented on [Academic Master](https://academic-master.com/)
Project designed and Implemented for [Academic Master](https://academic-master.com/)

