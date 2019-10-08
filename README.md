# Img2Vid

Senior Capstone Fall 2019

## Install


```
# set up virtualenvwrapper
pip install virtualenvwrapper
export WORKON_HOME=~/Envs
mkdir -p $WORKON_HOME
source /usr/local/bin/virtualenvwrapper.sh

# pip requirements
mkvirtualenv img2vid -python=`which python3.6`
setvirtualenvproject .
pip install -r requirements.txt

# start environment
jupyter notebook

```



