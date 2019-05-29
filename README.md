# t4-template

1. 替换 C:\Windows\Microsoft.NET\Framework\v4.0.30319\Config\machine.config
2. 添加 app.config 至项目根目录，用于存放连接字符串
3. 引入 T4 文件夹
4. 注册 GAC：PowerShell 管理员 -> cd 'C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.6.1 Tools' -> ./gacutil.exe /i dll路径/Npgsql.dll

脚本运行报引用错误，请找到相关dll重新注册GAC
直接运行报错请调试运行
