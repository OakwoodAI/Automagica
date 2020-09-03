# Getting started

## Installing on Windows
Download Automagica and get started automating within 5 minutes through our website [automagica.com](https://www.automagica.com). 
Our one-click installer for Windows in combination with Automagica Flow is by far the easiest way to get started automating.

By signing up for the [Automagica Portal](https://www.portal.automagica.com), you also gain access to our specialized OCR-service and our Automagica Wand back-end, which features computer vision powered by machine learning for recognizing UI elements.

![](https://i.imgur.com/zsCjP8G.gif)

### Install through PyPi
Installation can also be done through `pip`, Python's best-known package manager. We advise Python 3.7 for the installation, as for this version all the dependencies are widely available for all platforms. Newer versions are currently not supported, however this is on our roadmap.

After you have installed Python 3.7 and `pip`, you can install Automagica through PyPi by running:
```
pip install automagica -U
```
Please note that the PyPi releases are not synchronized with the installer available through the [Automagica Portal](portal.md). It could happen that the PyPi version is slightly behind the version available through GitHub or the Automagica Portal.

## Installing on Linux

### Fedora-like distributions of Linux such as Red Hat Enterprise Linux or CentOS
You can install Automagica by running the following commands:

```
sudo yum install python3-devel chromium -y
sudo pip3 install automagica -U
```
### Debian-like distributions of Linux such as Ubuntu
You can install Automagica by running the following commands:
```
sudo apt-get install python3-devel chromium -y
sudo pip3 install automagica -U
## Installation on Linux
Interactive one-click examples with documentation can be found on [portal.automagica.com](https://portal.automagica.com)
```

## Your first automation

There are multiple ways to automate tasks with Automagica. Down below a short overview of the different editors and what type of user it is designed for.

- __[Automagica Flow](https://www.portal.automagica.com)__: a visual flow designer to build automations quickly with full support for Python code. Comes with Automagica Wand (UI element picker) integrated.
- __[Automagica Lab](https://www.portal.automagica.com)__: notebook-style automation development environment based on Jupyter Notebooks.
- __Bring your own editor__: more developer-oriented Automagicians can use Automagica in their trusted Python editor like Visual Studio Code, Sublime, etc..

Unless you are set on using your own editor, we recommend Automagica Flow for both first-time users and more experienced developers. Automagica Flow comes with all the core components installed and offers the possibility to build your automation in both code and a visual canvas with dynamic search and dropdown-menus.  In addition, for more seasoned Automagicians and Python developers, Automagica Flow also offers the flexibility to write or import custom Python code (.py) and Jupyter notebooks (.ipynb).

![](https://i.imgur.com/ps1Uhck.png)

## Experimental on-machine OCR
Signing up for the Automagica Portal gives you access to a specialized OCR-service. If you have not signed up, you can still use an OCR engine on your local machine, but the results may be poorer.

To use on-machine OCR, you'll need to install the open-source OCR engine `tesseract` on your machine. Follow the [installation instructions for your operating system](https://tesseract-ocr.github.io/tessdoc/Home.html) (Mac, Windows, and Linux supported).
