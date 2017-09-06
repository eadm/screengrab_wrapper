# Screengrab Wrapper
Tool to wrap screengrab screenshots in device frames &amp; etc

## How to use

Requres `Python 2`

First you need to install required libs

```sh
apt-get install libmagickwand-dev
pip install Wand
pip install PyYAML
pip install colorama
```

Then after you create screenshots with screengrap

```sh
python mover.py <path to folder with locales> <one of platform that specified in platforms.yml>
python wrapper.py <path to folder with locales> <one of platform that specified in platforms.yml>
```

As result you get wrapped screenshots that ready to be deployed with `supply`
