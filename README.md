# atom-config

```bash
sudo add-apt-repository ppa:webupd8team/atom
sudo apt update
sudo apt install atom silversearcher-ag git
pip install flake8

git clone git@github.com:ksindi/atom-config.git ~/.atom
cd ~/.atom
apm install --packages-file my-packages.txt
```

## Generate list of packages

```bash
cd ~/.atom
ls packages | xargs -n 1 echo | cut -d/ -f1 > my-packages.txt
```
