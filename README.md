README
========

NOTE
----

> 本文档使用debian/Linux（ubuntu/Linux相似）编辑

> windows 请安装相关软件

安装Sphinx
------------

```
pip install sphinx sphinx-autobuild sphinx_rtd_theme
```

支持markdown编写
--------------------

```
pip install recommonmark
```

生成html
-----------

```
make help
make html

firefox build/html/index.html
```

生成pdf
----------

```
sudo apt-get install texlive-full
make latexpdf

firefox build/latex/debug-learning.pdf
```

查看文件
---------

```
build/
├── html
|   └── index.html
└── latex
```


Sphinx 文档
------------------------------------------------------------------------------


[Sphinx 使用手册](https://zh-sphinx-doc.readthedocs.io/en/latest/index.html)

[Docutils 项目](https://docutils-zh-cn.readthedocs.io/zh_CN/latest/index.html)

