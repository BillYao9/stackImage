# stackImage
学习中遇到的一个小功能,改进了一下

功能很简单
使用方法, import stackImage
imshow(imgarray,scale,windowname)

imgarray 支持数组,或二维数组

imgs = [img, img ,img ]
imgs = [[img, img],[img, img, img]] 支持不同的元素数目 以最大的维数做为图片的宽度
一维数组支持任意长度,超过屏幕宽度时自动换行
scale 默认为1
windowname 也是选项
