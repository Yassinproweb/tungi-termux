# Tungi Termux

Simple script to change color-schemes and fonts for [Termux](https://termux.com) terminal emulator.

> **`tungi-termux` provides color-schemes and powerline-ready fonts to customize the appearance of the Termux terminal.**

### How to install

Follow the steps below - 

```bash
# Go to home dir - 
cd $HOME

# Clone this repository (use `gh repo clone Yassinproweb/tungi-termux` if you want to use the GitHub CLI)- 
git clone https://github.com/Yassinproweb/tungi-termux

# Change to tungi-termux dir -
cd tungi-termux

# To install it, run -
./install

# And follow the steps, it'll be installed on your system.
```

### Run

Run `tungi-termux` & select the right option -

```bash
$ tungi-termux
  ┌───────────────────────────────────────────────────┐
  │░░▀█▀░█░█░█▀█░█▀▀░▀█▀░░░░░▀█▀░█▀▀░█▀▄░█▄█░█░█░█░█░░│
  │░░░█░░█░█░█░█░█░▄░░█░░▄▄▄░░█░░█▀▀░█▀▄░█░█░█░█░▄▀▄░░│
  │░░░▀░░▀▀▀░▀░▀░▀▀▀░▀▀▀░░░░░░▀░░▀▀▀░▀░▀░▀░▀░▀▀▀░▀░▀░░│
  └───────────────────────────────────────────────────┘
    [*] By- Yassin Katungi // Yassinproweb

    [C] Colors (5)
    [F] Fonts (11)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 5 unique color-schemes.
+ 11 powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* or *file URL*.
+ Set colors and fonts in place.

### Use Import
```bash
    [Select Option]: 4

    [1] Local File (Enter path to file)
    [2] Internet File (Enter File URL)

    [Select Option]: 2

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/Yassinproweb/tungi-termux/main/colors/rosepine.properties

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (e.g. - `/data/data/com.termux/files/home/tungi-termux/rosepine.properties`) of the color-scheme.
+ To import *web file*, enter the file url (e.g. - `https://raw.githubusercontent.com/Yassinproweb/tungi-termux/main/colors/rosepine.properties`) of the color-scheme.
<br />

### Previews

|Colorschemes|Fonts|
|--|--|
|![img](images/colors.gif)|![img](images/fonts.gif)|

|Import - URL|Import - Local|
|--|--|
|![img](images/url.gif)|![img](images/local.gif)|

|Install|Uninstall|
|--|--|
|![img](images/install.gif)|![img](images/uninstall.png)|

### FYI
- An `uninstall` script is also added, in case you want to remove this program.
- Again... If you can improve it, sure...
- Have fun!
