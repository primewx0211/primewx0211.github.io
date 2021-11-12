​

**（1）外星人**——复制粘贴发现...flag出来了...
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021092913540524.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)

**（2）view_source**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135415445.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)

根据提示，查看码源
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135423251.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)


**（3）一个不能按的按钮**

打开发现按钮按不了
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135431738.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
 将post改为ture
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135439129.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
删掉"disable=""， 刷新
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135446555.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
 按钮可以按了，按下得到flag
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135503437.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)**（4）ezsy_request**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135550940.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
根据提示，应该是get或者post请求。打开，首先是get请求
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135734839.jpg)
     a.直接拼接

![](https://img-blog.csdnimg.cn/20210929135757122.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)

  b.用postman传参
     ![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135720726.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)继续根据提示，用postman进行post传参，得到flag
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135630253.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
 **（5）夹心饼干**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135809452.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)根据提示，是个经典的cookie题，拼上cookie.php
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135822658.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
 根据提示查看response，找到flag
​![在这里插入图片描述](https://img-blog.csdnimg.cn/20210929135832865.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzYwODAxNjQ4,size_16,color_FFFFFF,t_70)
