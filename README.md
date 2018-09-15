# inakidelamadrid.github.io
Personal Blog Made with Python Pelican

** Based on [Pelikan](http://docs.getpelican.com/en/stable/)**


## Installing
- Install a virtualenv

````
virtualenv -p python3 pyenv

````

- Activate the virtualenv

````
. pyenv/bin/activate
````

- Install the required python packages

````
pip install -r requirements.txt  
````


## Compiling new content
````
pelican content
````

## Preview your site

````
cd projects/yoursite/output
python -m pelican.server
````

