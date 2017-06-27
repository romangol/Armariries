Armariries
================================
        基于LLVM的支持多平台多语言的混淆器,目前仅开放了字符串加密.
###安装
```shell
mkdir obf
cd obf
clone git@github.com:flysoar/Armariries.git
cmake -DCMAKE_BUILD_TYPE:String=Release ./Armariries
make -j4
```

###用法

        编译时候添加命令行-mllvm -sobf,指定随机数生成器种子 -mllvm -seed=0xdeadbeaf

###名称由来-孤挺花

        取自细音启小说<黄昏色的咏使>以及<冰洁镜界的伊甸>中的人物孤挺花.寓意无人理解的守护.Armariries是作者自创语言selahpheno中孤挺花的意思.
