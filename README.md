# Python版CTPAPI

## 直接使用

openctp提供了pip install和文件下载两种方法安装CTPAPI-Python库，可以直接使用，均支持6.3.15~6.7.2各个版本。

### pip install方式

```bash
pip install openctp-ctp==6.7.2.* -i https://pypi.tuna.tsinghua.edu.cn/simple --trusted-host=pypi.tuna.tsinghua.edu.cn
```

### 文件下载方式

[CTPAPI-Python接口下载](http://openctp.cn/download.html)

## 自己编译
CTPAPI-Python使用Swig技术开发，可以自己按以下步骤编译，需要安装swig等组件，详细攻略见：[CTPAPI-Python开发攻略](https://zhuanlan.zhihu.com/p/688672132)。

### Windows编译

#### Win32
```
cd 6.3.15
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

#### Win64
```
cd 6.3.15
mkdir build
cd build
cmake -A x64 ..
cmake --build . --config Release
```

### Linux编译
```
cd 6.3.15
mkdir build
cd build
cmake ..
cmake --build . --config Release
```