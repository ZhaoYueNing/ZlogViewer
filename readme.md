# ZlogViewer

日志查看器，浏览器实时展示服务器日志

![image-20200304114919444](https://tva1.sinaimg.cn/large/00831rSTly1gchr45v16hj31fy0fmn5i.jpg)



## 使用方式

### 编辑配置文件

```
vim ~/.zlog/config.json

{
  "logFiles": [
    {
      "sourceId": "DemoLog",
      "filePath": "/Users/zhaoyuening/.zlog/demo.log"
    },
    {
      "sourceId": "Demo2Log",
      "filePath": "/Users/zhaoyuening/.zlog/demo2.log"
    }
  ]
}
```

### 启动程序

```
nohup java -jar zlog-0.0.1-SNAPSHOT.jar --server.port=8080 &
```

### 访问浏览器

http://localhost:8080

![image-20200304115258328](https://tva1.sinaimg.cn/large/00831rSTly1gchr7wi6elj31gu0ltalz.jpg)