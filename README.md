# -魔方idc-免费
仅供学习和参考，请在下载后二十四小时之内自行删除，责任自负。

下载我提供的安装包

需要安装php扩展。根据网站要使用的php版本，下载扩展文件到仓库根目录下载对应的，上传到php安装目录 /lib/php/extensions/no-debug-non-zts-xxxx（xxxx为一串数字）文件夹里面。

修改phpini 末尾添加这一行 重载配置

extension=idcsmart73.so(如果你是php7.2那就将php73修改为72如果是7.4版本同理
