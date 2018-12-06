# 历史记录上传

## 获取历史数据库列表
### 接口：/api/selectHisRecord
### 额外参数

### 返回值
成功返回值 
>  {file:历史数据列表}


* * * 
## 上传历史数据库
### 接口：/api/uploadHisRecord
### 额外参数

[cutSize]()
> 分割大小

[index]()
> 第几个文件，从0开始

[file]()
> 路径名|文件名

### 返回值
成功返回值 
> body 文件二进制
  header
	result,{error:error}
	result:{result:1,md5:md5文件值}


* * * 
## 删除历史数据
### 接口：/api/deleteHisRecord
### 额外参数

[file]()
> 路径名|文件名}(格式)

### 返回值
成功返回值 
>  {result:1}