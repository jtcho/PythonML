# Python Machine Learning

## Getting Started

It is advisable to install virtualenv for working with multiple Python versions on a single machine. 

### Setting Up virtualenv

#### OSX
Install Python 3 from [package](https://www.python.org/downloads/). This allows you to run `python3` and `pip3`. Software is installed into `/Library/Frameworks/Python.framework/Versions/3.x/bin/`. 

Install virtualenv for Python 3 for the user only (which is placed into ~/Library/Python/3.x/bin):

```
$ pip3 install --user virtualenv
```

Create the following alias in your `~/.bash_profile`:

```
echo "alias virtualenv3='~/Library/Python/3.x/bin/virtualenv'" >> ~/.bash_profile
```

To activate the virtualenv for Python 3, then run:
```
source ./bin/activate
```

### Installing Dependencies
Once you have the virtualenv active, you may use pip to install requirements from the requirements file:

```
pip install -r requirements.txt
```
