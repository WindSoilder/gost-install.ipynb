# 通过 Jupyter Notebook 安装 GOST

## 重要提示

**下面的操作都是在自己本地的电脑上完成，不需要在服务器上操作，这个 notebook 的功能就是把服务器上软件安装配置的过程变成了代码，会自动帮你在服务器上把软件安装好配置好。**

## 在 Datalore 上运行，免科学上网(推荐)


[![Open In Datalore](https://datalore.jetbrains.com/logo.ico)](https://datalore.jetbrains.com/notebook/JQtV8X5iGGaNh33MHbfc8G/wlOSxnyYSq2u5TRQjJHAf1/) 

## 在 Colab 上运行

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lewangdev/gost-install.ipynb/blob/main/gost_install.ipynb) 

## 在自己电脑上运行

### 安装 Python 环境

如果不会安装，请问 ChatGPT

### Windows 上

```sh
git clone https://github.com/lewangdev/gost-install.ipynb.git
cd gost-install.ipynb

python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
```

### MacOS 或者 Linux 上

```sh
git clone https://github.com/lewangdev/gost-install.ipynb.git
cd gost-install.ipynb

python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

## 运行 jupyterlab

```sh
jupyter-lab
```

## 操作

* 浏览器打开 http://localhost:8888/lab/tree/gost_install.ipynb
* 根据提示一步一步执行即可
