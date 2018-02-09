# TestEnvironment
Test environment required all


Required installation tools(due to size limitation in GitHub, so some tools only provide path):
1. jre-8u151-windows-i586_8.0.1510.12.exe
2. tesseract-ocr-setup-4.0.0-alpha.20170804.exe   
https://pan.baidu.com/s/1i6hvNwT


OCR图像识别工具服务器配置文档1.2.docx  -- 也算是一个安装测试环境的文档，可以参照它来安装测试环境

PictureConverter.rar是图片转换工具
 
网盘中的data.zip解压后放到类似于这个文件夹中C:\Program Files (x86)\Tesseract-OCR\tessdata，
图像识别 工具PictureConverter.rar解压后放到C:\Program Files (x86)\Tesseract-OCR，一共两个文件，这样的话按照文档设置环境变量后，
PictureConverter.exe（图像识别工具）就能直接运行，具体的方法在我的另一个文档（程序具体实现.docx）中有详细介绍。
测试 用的数据是网盘中的2017112301102-001.zip和Test_Image.zip

白话 ：
安装 上面的那两个exe，然后设置环境变量，再把data.zip中的文件和PictureConverter.rar中的文件放到指定路径，齐活~！
