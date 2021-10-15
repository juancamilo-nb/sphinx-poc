# SPHINX: (https://www.sphinx-doc.org/)

Python Documentation Generator

to start just install sphinx (it is in the requirements)


```
pip install requirements.txt
```

and initiate the doc generator script


(I created an extra directory for sphinx because in /docs is where the github page is going to live)


```
sphinx-quickstart docs/sphinx
```

Run this command inside the sphinx directory to generate the source files that generate the documentation

```
sphinx-apidoc -o source ../.. --ext-autodoc
```

finally run the next command to generate the html files that we are going to see on github pages

```
make html
```

# Github pages

To add a google page for a project you just need to go to the settings



![](https://github.com/juancamilo-nb/sphinx-poc/blob/master/images/01.png)



go to pages in the side menu


![](https://github.com/juancamilo-nb/sphinx-poc/blob/master/images/02.png)



and there you have the options

to activate the page you just need to select a branch in your repo and the dir where the page is going to live


![](https://github.com/juancamilo-nb/sphinx-poc/blob/master/images/03.png)


## The good thing:
You can change the url and domain for a custom domain including subdomains.

## The bad thing:
There aren't many options to change where your webpage is going to live inside the project.
Basically you have / or /docs options, nothing more.
