# Course Project Documentation
CS120 Computer Networks @ShanghaiTech

## Build
The document is created with [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) and hosted at https://sist-cs120.github.io/project-doc/.

```
$ git clone https://github.com/sist-cs120/project-doc.git
$ docker run -it --rm -v /absolute/path/to/project-doc:/docs sphinxdoc/sphinx-latexpdf make clean html
```
or
```
$ docker run -it --rm -v /absolute/path/to/project-doc:/docs sphinxdoc/sphinx-latexpdf make latexpdf
```
