# atom-config

## Set Up

```bash
sudo add-apt-repository ppa:webupd8team/atom
sudo apt update
sudo apt install atom
```

or install by downloading from https://atom.io/

```bash
sudo dpkg -i atom-amd64.deb
```

Clone repo:

```bash
git clone git@github.com:ksindi/atom-config.git ~/.atom
cd ~/.atom
apm install --packages-file my-packages.txt
```

## Generate list of packages

```bash
cd ~/.atom
ls packages | xargs -n 1 echo | cut -d/ -f1 > my-packages.txt
```

## Useful shortcuts

| Action           | Shortcut     | Source        |
| ---------------- | ------------ | ------------- |
| Refactor         | ctrl+alt+u   | python-tools  |
| Goto Definition  | ctrl+alt+g   | python-tools  |
| Beautify         | ctrl+alt+b   | atom-beautify |
| Fuzzy file find  | ctrl+t       | atom-beautify |
| Find text        | ctrl+shift+f | atom          |
| Copy line down   | ctrl+shift+d | atom          |
| Move line up     | ctrl+up      | atom          |
| Move line down   | ctrl+down    | atom          |
| Uppercase        | ctrl+k+u     | atom          |
| Lowercase        | ctrl+k+l     | atom          |
| Preview markdown | ctrl+shift+m | atom          |

https://github.com/nwinkler/atom-keyboard-shortcuts
