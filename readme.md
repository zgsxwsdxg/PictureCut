![pic](picture/logo.png)
#票据裁剪控件
##简介
票据图片采集过程易受到复杂背景干扰和光照不足或不均等不利影响,使得自动、准确、实时裁

![pic](picture/3.png)
![pic](picture/4.png)



![pic](picture/pic1.png)

##方法
* 第一步,票据自动纠偏:采用自适应阈值 Canny 算子提取灰度图边缘,再通过 Hough 变换 确定票据偏转角度,进而完成票据纠偏;
