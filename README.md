# Course Project Documentation
CS120 Computer Networks @ShanghaiTech

## Build
The document is created with [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html). 

Currently, figures are in .svg format, pdf build is not supported. 

```
$ git clone https://github.com/sist-cs120/project-doc.git
$ docker run -it --rm -v /absolute/path/to/project-doc:/docs sphinxdoc/sphinx:6.2.1 make html
```
Build twice to fix numref bugs. 
```
$ docker run -it --rm -v /absolute/path/to/project-doc:/docs sphinxdoc/sphinx make html
```
