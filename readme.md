
1. 使用时 需要修改 63342为本地的端口
    var port = process.env.PORT|| 63342;

2. 设置要代理的到的地址
   proxy.setProxy(app,'/','http://192.168.100.90/api');
