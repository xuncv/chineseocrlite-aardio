# chineseocrlite-aardio
#### chineseocrlite的aardio支持库

基于[chineseocr_lite](https://github.com/DayBreak-u/chineseocr_lite) 项目，针对aardio特性，制作的dll动态链接库。

所用技术：

1. crnn dbnet
2. onnx
3. opencv

##### 用法：

第一种：下载[ocrLite库](https://github.com/xuncv/chineseocrlite-aardio/releases/download/0.0.1/ocrLite.zip)，放到aardio开发环境的lib目录下。

第二种：自动安装

```
允许使用 _IMPORTURL 注册远程扩展库网址，例如：

_IMPORTURL.ocrLite = "https://github.com/xuncv/chineseocrlite-aardio/releases/download/0.0.1/ocrLite.tar.lzma"
import ocrLite;

也可以在aardio中单独运行下面的代码安装远程扩展库：

import ide;
ide.installLib("ocrLite","https://github.com/xuncv/chineseocrlite-aardio/releases/download/0.0.1/ocrLite.tar.lzma")

```

![santi](./santi.png)



![santi-result](./santi-result.png)

