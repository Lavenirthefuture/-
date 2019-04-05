# -
如果图片分辨率过高，训练时会进行缩放。这段代码主要用来一次性裁剪图片，修改标注文件并且生成测试图片。

标注文件格式（txt）应该为


一行一张图片的数据
图片路径 xmin,ymin,xmax,ymax,类别 xmin1,ymin1,等等

适用于github上star最多的keras-yolov3项目
