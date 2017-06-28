Armariries
================================
## 中文
基于LLVM的支持多平台多语言的混淆器,目前仅开放了字符串加密.
### 安装
```shell
mkdir obf
cd obf
clone git@github.com:flysoar/Armariries.git
cmake -DCMAKE_BUILD_TYPE:String=Release ./Armariries
make -j4
```
### 用法
编译时候添加命令行-mllvm -sobf,指定随机数生成器种子 -mllvm -seed=0xdeadbeaf
### 名称由来-孤挺花
取自细音启小说<黄昏色的咏使>以及<冰洁镜界的伊甸>中的人物孤挺花. 她即便无人理解依然守护着姐姐与世界. Armariries是作者自创语言Selahpheno中孤挺花的意思.

## English
An obfuscator bases on llvm for multiple language and platform. Right now, only string obfuscation is available.
### Install
```shell
mkdir obf
cd obf
clone git@github.com:flysoar/Armariries.git
cmake -DCMAKE_BUILD_TYPE:String=Release ./Armariries
make -j4
```
### Usage
Add instruction -mllvm -sobf for opening string obfuscation when compile. Add instruction -mllvm -seed=0xdeadbeaf for setting random seed.
### Name origin - Amaryllis
Amaryllis is a character in light novel <黄昏色の詠使い> and <氷結鏡界のエデン> written by 細音啓(sazaneK). Although nobody comprehends she, she still guards her sister and the world. Armariries is the meaning of Amaryllis in conlang Selahpheno in sazaneK's light novel.