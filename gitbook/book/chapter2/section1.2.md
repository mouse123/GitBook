# 下载工程
### 接口：/api/projectDownload
### 额外参数

[projectUploader]()
>工程文件

[bigFileMd5]()
> 完整工程文件的Md5 当发送的切片文件是最后一个时，会额外发送该字段

[index]()
> 第几个文件，从0开始

[password]()
> 下载密码

[fileCount]()
> 分片次数

[smallFileMd5]()
> 切片工程文件MD5

[projectUploader]()
> 工程文件

### 返回值
成功返回值 
> {result:1}