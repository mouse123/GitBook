# 在线/离线更新
### 接口：/api/hmiUpdate
### 额外参数

[password]()
> 下载密码

[index]()
> 第几个文件，从0开始

[hmiPackDownloader]()
> 更新包文件

[smallFileMd5]()
> 切片工程文件MD5

[bigFileMd5]()
> 完整工程文件的Md5 当发送的切片文件是最后一个时，会额外发送该字段

[fileCount]()
> 分割总次数

### 返回值
成功返回值 
>  {result:1}