
# 启动服务器

在Way.EJServer\bin\Debug\netcoreapp2.0文件夹里面，创一个run.bat批处理文件，内容如下：

```code
dotnet Way.EJServer.dll 6060
```

6060是本机任意一个没有使用的端口号，表示以6060为端口，创建一个服务器工作空间

# 运行客户端

运行EJClient\bin\Debug\EJClient.exe程序,连接到服务器6060工作空间
server url:https://localhost:6060
user name: sa
password:  1