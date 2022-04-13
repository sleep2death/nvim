# nvim

1. 克隆仓库
1. 克隆 submodule：`git submodule init && git submodule update`
1. [安装编译软件](https://github.com/neovim/neovim/wiki/Building-Neovim#build-prerequisites):
   - Ubuntu: `sudo apt-get install ninja-build gettext libtool libtool-bin autoconf automake cmake g++ pkg-config unzip curl doxygen`
   - Mac/Homebrew: `xcode-select --install`，安装[Homebrew](https://brew.sh/)，`brew install ninja libtool automake cmake pkg-config gettext curl`
1. [编译](https://github.com/neovim/neovim/wiki/Building-Neovim):
   - `cd neovim && make`
   - `sudo make install`
