# atom-config

```bash
git clone git@github.com:ksindi/atom-config.git ~/.atom
apm install --packages-file my-packages.txt
```

## Requirements

```bash
sudo add-apt-repository ppa:webupd8team/atom
sudo apt update; sudo apt install atom
pip install flake8
sudo apt install silversearcher-ag
```

Note to remove atom: `sudo apt remove --purge atom`

## Generate list of packages

```bash
ls packages | xargs -n 1 echo | cut -d/ -f1 > my-packages.txt
```
