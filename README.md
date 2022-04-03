# CameraControl
描述：调用摄像头拍照并通过邮件发送到指定邮箱

[博客地址:“悄无声息”地获取你的照片](https://cosmicdusty.cc/post/%E6%82%84%E6%97%A0%E5%A3%B0%E6%81%AF%E8%8E%B7%E5%8F%96%E4%BD%A0%E7%9A%84%E7%85%A7%E7%89%87)

[murphyhoucn/CameraControl](https://github.com/murphyhoucn/CameraControl)

# 使用

使用 git 将仓库代码 clone 到本地或者下载打包好的 .zip 仓库文件。

``` bash
git clone https://github.com/murphyhoucn/CameraControl
```

文件目录结构


``` bash
D:\Develop_GitHub\MurphyHouCN\CameraControl
├─.gitignore
├─CameraControl.exe //未上传
├─CameraControl.py
├─ICON.ico
├─LICENSE
├─README.md
├─.git
```

通过对`CameraControl.py`程序文件进行必要的更改，可以直接运行该程序，或是是将文件更改好之后通过在`命令行`输入如下命令打包生成`.exe`文件后再运行。

```bash
pyinstaller -F -w -i ICON.ico .\CameraControl.py
```

# 学习

`CameraControl.py`使用的算法在博客中有介绍：[博客地址：悄无声息获取你的照片](https://cosmicdusty.cc/post/%E6%82%84%E6%97%A0%E5%A3%B0%E6%81%AF%E8%8E%B7%E5%8F%96%E4%BD%A0%E7%9A%84%E7%85%A7%E7%89%87)

# 交流

如果有什么问题/想法可以通过以下方式，提出您的问题/想法：

1. 在GitHub仓库中提出一个Issues
2. 通过邮件联系到我：[Murphy](mailto:Murphy0928Hou@outlook.com)
3. 在博文最下面的评论区留下您的问题/想法