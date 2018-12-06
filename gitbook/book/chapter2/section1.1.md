# 分片文件
### 接口：/api/getFileCount
### 额外参数
#### 如果是上传工程文件
- [fileType]()
>文件类型

- [cutSize]()
>文件切割大小

#### 如果是历史记录数据库文件

- [fileType]()
>文件类型

- [cutSize]()
>文件切割大小

- [file]()
>路径名|文件名}(格式)

### 返回值
成功返回值 
>{fileCount:分片次数，md5:文件md5值}