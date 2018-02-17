# auto_reply
## 使用说明
在安装好Python开发环境的前提下，再使用以下命令安装两个库。
> pip install itchat pillow

最好在命令提示符中运行，在PyCharm中运行时生成的二维码会乱。
> python index.py

初始版本没有添加 replied 列表用来存储已回复祝福语的用户，使得重复回复显得很尴尬。另外使用祝福语大全API替代固定的回复短语。

## 参考资料
代码实现参考了知乎：https://zhuanlan.zhihu.com/p/25034403
