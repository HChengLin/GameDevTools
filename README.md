# GameDevTools
游戏开发日常用到的工具集

将GameDevTools.bat 创建快捷方式 放到桌面就可以快速打开

# 搜索工具

输入关键字，搜索工具

比如想获取字符串md5，输入md5搜索，则会列出md5 相关工具

输入工具序号，即可使用工具

# 新增工具
在GameDevTools.py 注册新的工具 与 关键字

```
toolSets=\
{
    # 注册程序 与 关键字，关键字有多个
    # Module:['keyword1','keyword2']

    # 获取文件MD5
    GetFileMD5:['md5','file md5','file'],

    # 获取字符串MD5
    GetStrMD5:['md5','string md5','string','str md5'],

    # 获取 10位 Unix时间戳 单位秒
    GetUnixTimeStamp:['unix','time','timestamp'],

    # 获取 13位 Unix时间戳 单位毫秒
    GetUnixTimeStamp_ms:['unix','time','timestamp','ms'],

    # MultiSizeIcon
    MultiSizeIcon:['icon','icon size'],
}
```
