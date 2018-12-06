# HMI 云管理器
> 通过云组态操作HMI.

## 云服务接口
> 云地址(http://cloud.haiwell.com).

- [用户登录](chapter1/section1.1.md)
- [获取设备](chapter1/section1.2.md)
- [用户注销](chapter1/section1.3.md)

## HMI接口
> HMI地址(http://{machineCode}.haiwell.com:8000).

- [分片文件](chapter2/section1.1.md)
- [下载工程](chapter2/section1.2.md)
- [上载工程](chapter2/section1.3.md)
- [在线/离线更新](chapter2/section1.4.md)
- [更新hmi时间](chapter2/section1.5.md)
- [历史记录上传](chapter2/section1.6.md)
- [获取HMI信息](chapter2/section1.7.md)
- [HMI在线状态](chapter2/section1.8.md)

## 错误码表(HMI接口)
- [1000]()
> 用户无访问权限
- [1001]()
> HMI异常错误
- [1002]()
> 文件md5值匹配错误
- [1003]()
> HMI下载密码错误
- [1004]()
> 工程密码错误
- [1005]()
> 该分片文件已经处理过

## 返回值格式(HMI接口)
``` bash
{result:value} # success
{error:errorCode} # error
```

## License

[MIT](http://opensource.org/licenses/MIT)
