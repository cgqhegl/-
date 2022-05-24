# Baidu-picture-crawler
一个用python编写的爬虫程序

python环境是3.8的，这个没有版本限制，运行之前请先安装requests模块就好了：
```
python3.8以上：pip3 install requests</br>
python其他版本：pip install requests
```

安装完之后就可以运行了，它会坚持绝对路径下有没有images文件夹,</br>
如果没有的话会自行创建，如果存在的话就把下载下来的图片存储在images文件夹里面

可以把我写的那个删掉，那些是没必要的。就是下面这一行：
```
39：print('制作者：陈拾\n作者博客：https://cs.scsn.top')
```
如果你也想打包文件的话也可以下载pyinstaller模块来打包，下载时候执行：
```
pyinstaller -F main.py
```
！注意！这里的main.py是自己想要打包的文件名！！！
