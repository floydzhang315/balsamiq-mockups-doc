# 我可以在微软 Sharepoint 服务器上保存 Mockups 文件吗？

**最近已经上传完毕！** 
   
这篇网页是为了 [Balsamiq Mockups 3](https://balsamiq.com/products/mockups/) 而上传的。原来的文件您可以点击[这里](http://media.balsamiq.com/files/Balsamiq_Mockups_v1-v2_Docs.pdf)来观看。  

如果您想要在微软 Sharepoint 服务器上保存 Mockups 文件，您需要让您的服务器管理员在 IIS 上添加下列的 mime 类型。

```
.bmpr  application/vnd.balsamiq.bmpr
```
