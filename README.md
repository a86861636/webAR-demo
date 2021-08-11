
<h1 align="center">用AR.js做图片追踪的Demo</h1>

实现打开手机摄像头，对图片（smoking_boy.jpg）进行追踪，显示模型并且可旋转缩放。
需要https协议才能打开摄像头，把项目放到服务器上，用手机打开网站。

AR.js项目地址
https://ar-js-org.github.io/AR.js-Docs/image-tracking/
旋转功能项目地址 arjs-gestures 
https://github.com/fcor/arjs-gestures

替换想要追踪的图片
把图片训练成AR.JS能够识别的形式，图片训练有web版和node版。
选择识别度高，分辨率高的图片，否则会识别不出来。
训练文件越大，等待时间越长，训练完成后替换掉nft里面的文件。

web版
https://carnaux.github.io/NFT-Marker-Creator/#/
正确返回下载的3个文件格式分别是 .fset .fset3 .iset

node版
https://github.com/Carnaux/NFT-Marker-Creator

替换模型
把model里面的文件进行替换