FaceMask_Yolov4Tiny代码调试 Face mask detection yolov4 tiny

原项目地址：

改动：

1.原项目中软连接

2.加了一些打印当前工作目录的命令

3.保存图片的按钮加上汉字说明

使用：

1.参照原项目中的步骤下载数据集并重命名

2.将本项目代码上传至谷歌云盘

3.在Colab中运行yolov4_tiny.ipynb

4.训练过程太长，打开/dada 下的 cfg 文件把max_batches = 6000 改小一点(若出错则可能steps也要改)

5.打开摄像头时点左上角按钮保存图片
