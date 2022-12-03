# docker-datascience-cpu

"docker-datascience-cpu" is a simple/easy-to-use template for setting up a python data science environment using Docker & VScode.

## Features

* **Jupyter notebook** with VScode

* Useful extensions & libraries are available

  * Ubuntu-22.04 packages
    * git
    * vim
    * powerline

  * VScode extensions
    * git extensions
    * code highlight & completion

  * libralies for **Japanese Python users**
    * Mecab (mecab-ipadic-neologd)
    * japanese_matplotlib

* workspace that **can be shared with the host**

* (**GPU** unavailable in container)

## Requirement

* Docker>=20.10.16
* Docker-Compose>=2.6.0
* VScode>=1.73.1
* Dev Container>=0.264.0
* git

## Installation

1. Download [Docker-Desktop](https://www.docker.com/products/docker-desktop/) and setup
2. Download [VScode](https://azure.microsoft.com/ja-jp/products/visual-studio-code/) and setup
3. Download [Remote Development](https://code.visualstudio.com/docs/remote/remote-overview#_getting-started) in VScode
4. Download [Git](https://git-scm.com/downloads) and setup

## Usage

1. Clone this repository

```bash
git clone https://github.com/hayashizaki-yu/docker-datascience-cpu.git
```

2. Open this folder with VScode
   * Click "files" in the upper left corner of VScode screen
   * Click "Open folder"
   * Select this folder

3. Open Container with Dev container
   * Click "><" icon in the lower left corner of VScode screen
   * Select "Reopen in container"
   * Initially it takes a while to start up

4. restart VScode
   * Initially, VScode extention for python will not be installed
   * You can resolve this problem by restarting VScode

## Extra: install [pytorch](https://pytorch.org/) or [tensorflow](https://www.tensorflow.org/?hl=en)

* pytorch
  * run the command in container

```bash
pip install torch torch vision torchaudio
```

* tensorflow
  * run the command in container

```bash
pip install tensorflow
```

## License
"docker-datascience-cpu" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
