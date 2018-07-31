---
layout: page
title: Preparation
---

## Prepare for the tutorials

To prepare your laptop for the CAP tutorial, make sure you have installed the latest version of [GAP](http://www.gap-system.org), [Singular](http://www.singular.uni-kl.de),
[homalg](http://homalg-project.github.io), [AutoDoc](https://gap-packages.github.io/AutoDoc) and [CAP](http://homalg-project.github.io/CAP_project).

The following installation instructions are for Ubuntu Linux. If your Laptop runs Windows 10, you can use the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10).

For those who are not able to bring their own computer or install GAP on it, we will provide computers to participate in the tutorials.

### Install Singular

It is sufficient to install the packaged version of Singular, via
{%highlight bash%}
sudo apt-get install Singular
{%endhighlight%}
For other installation options, please visit [the Singular installation page](https://www.singular.uni-kl.de/index.php/singular-download.html).

### Install GAP

You can download, compile, and install GAP via the following commands
{%highlight bash%}
sudo apt-get install autoconf build-essential m4\
                     libreadline6-dev libncurses5-dev wget \
                     unzip libgmp3-dev cmake gcc g++
wget https://www.gap-system.org/pub/gap/gap-4.9/tar.gz/gap-4.9.2.tar.gz
tar xf gap-4.9.2.tar.gz
rm gap-4.9.2.tar.gz
cd gap-4.9.2
./configure
make
cd pkg
../bin/BuildPackages.sh
{%endhighlight%}

Make sure you use this version of GAP and not the one you install via `apt-get`.

### Install packages

Make sure you have git installed:
{%highlight bash%}
sudo apt-get install git
{%endhighlight%}

Afterwards, move to the GAP package folder (if you have just compiled and installed GAP with the instructions above, you are
already there) and execute
{%highlight bash%}
git clone https://github.com/gap-packages/AutoDoc
git clone https://github.com/homalg-project/homalg_project
git clone https://github.com/homalg-project/CAP_project
{%endhighlight%}