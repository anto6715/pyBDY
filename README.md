# pyBDY for IRIDE workflow

The offical readme is available here: [README](README_ori.md)

<!-- TOC -->
* [pyBDY for IRIDE workflow](#pybdy-for-iride-workflow)
  * [How to install it](#how-to-install-it)
    * [Java](#java)
    * [Conda Environment](#conda-environment)
    * [pyBDY](#pybdy)
  * [How to use it](#how-to-use-it)
<!-- TOC -->

## How to install it

### Java

Download **JDK 11**

```shell
wget https://download.java.net/openjdk/jdk11.0.0.1/ri/openjdk-11.0.0.1_linux-x64_bin.tar.gz
tar -xvzf openjdk-11.0.0.1_linux-x64_bin.tar.gz
rm openjdk-11.0.0.1_linux-x64_bin.tar.gz
```

### Conda Environment

Install pybdy conda environment

```shell
conda create --name pybdy --file spec_pybdy_v0.1.txt
```

### pyBDY

Install pybdy

```shell
conda activate pybdy
pip install -e .
```

## How to use it

- Configure JAVA

```shell
export JAVA_HOME=/users_home/cmcc/adrinemobfm/lib/jdk-11.0.0.1
```

- Load conda environment

```shell
conda activate pybdy
```

- Run the tool

```shell
pybdy -s <NAMELIST>
```
