# atom-config

```
git clone git@github.com:ksindi/atom-config.git ~/.atom
apm install --packages-file my-packages.txt
```

to generate the packages

```
ls packages | xargs -n 1 echo | cut -d/ -f1 > my-packages.txt
```
