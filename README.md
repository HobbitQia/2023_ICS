# 2023_ICS_Course_Material

本仓库用来发布《计算机系统概论》课程笔记和实验内容，你可以直接查看[在线文档](https://hobbitqia.github.io/2023_ICS)，或将本仓库拉至本地部署。

本文档面向对象主要为浙江大学 2022-2023 短学期《计算机系统概论》助教为 [@HobbitQia](https://github.com/hobbitqia) 的同学，其他同学也可参考本文档。

本文档的部分内容借鉴了 2022-2023 春夏《计算机组成与设计》刘海风老师班课程的[实验文档](https://guahao31.github.io/2023_CO/)，同时也非常感谢《计算机系统概论》课程老师与历届助教在课程建设上的努力！

## 如何在本地构建？

本文档使用 [mkdocs](https://www.mkdocs.org/) 构建，并使用了 [material](https://squidfunk.github.io/mkdocs-material/) 第三方主题，你需要在本地依次序安装 [Python](https://python.org)、mkdocs、material 主题、heti 插件。

### Python 安装

官网[安装指导](https://wiki.python.org/moin/BeginnersGuide/Download)已经给出各系统安装方式，根据官网内容安装即可。

### mkdocs、material 主题、插件

均可以通过 [pip](https://pypi.org/project/pip/)（Python 的包管理器） 进行安装。

```bash
$ pip install mkdocs
$ pip install mkdocs-material
$ pip install mkdocs-heti-plugin
```

具体地，你可以分别查看 [mkdocs 的安装指导](https://www.mkdocs.org/getting-started/#installation) 与 [material 的安装指导](https://squidfunk.github.io/mkdocs-material/getting-started/#installation)。

### 本地构建

你只需要将本仓库拉至本地，后使用 `mkdocs serve` 部署即可。

```bash
# 拉取仓库，两者皆可
$ git clone git@github.com:hobbitqia/2023_ICS.git
$ git clone https://github.com/hobbitqia/2023_ICS.git
# 构建
$ cd ./2023_ICS
$ mkdocs serve
```

如果你使用本地部署查看文档，请在每次使用前查看并拉取远程仓库的 `master` 分支更新 `git pull`。

请注意，如果你使用本地构建，**需要自行保证使用的是最新版本的实验指导，因为未及时得知版本更新造成的后果自行承担**。

## 如何提建议

本人水平有限，文档难免有错误以及排布不合理之处。

如果你：

* 发现文档有知识性或实践性的错误
* 发现文本中的错别字/格式错误/图片缺失
* 对文档有建议

欢迎提交 Issue 或通过邮箱与我沟通，我的邮箱为 hobbitqia@zju.edu.cn 。

非常期待得到你的反馈！