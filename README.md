# YomkServerPy 简介

## 编译
1. pip install cython readerwriterlock【安装cython工具】
2. sudo apt update && sudo apt install gcc python3-dev 【安装gcc、python】
3. cd YomkServerPy
3. mkdir build && cd build
4. cmake .. -DCMAKE_INSTALL_PREFIX=~/YomkServerPy/install
5. cmake --build . --target install --config Release

## test
1. export PYTHONPATH=$HOME/YomkServerPy/install/lib/python3.10/site-packages:$PYTHONPATH 【根据实际安装目录编写】
2. cd YomkServerPy/test
3. python3 TestYomkService.py


