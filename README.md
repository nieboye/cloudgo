# Cloudgo
使用了 negroni, mux, render库
可以通过命令行参数 -p 指定监听的端口号
能够处理 /hello/{id} 和 /show/{filename} 两种请求参数

### 运行截图

 - **/hello/{id}**

![在这里插入图片描述](https://img-blog.csdnimg.cn/2018111917543076.JPG)

 - **/show/{filename}**
 ![在这里插入图片描述](https://img-blog.csdnimg.cn/20181119175618717.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2EyNDk2NDgxNTc=,size_16,color_FFFFFF,t_70)
 
### curl 测试
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181119175752831.JPG)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181119175800577.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2EyNDk2NDgxNTc=,size_16,color_FFFFFF,t_70)
### ab 测试
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181119175831649.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2EyNDk2NDgxNTc=,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20181119175839393.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2EyNDk2NDgxNTc=,size_16,color_FFFFFF,t_70)
### 重要参数解释
 - Server Software: 服务器使用的软件，即响应头的 Server 字段
 - Server Hostname: 服务器主机名，即请求头的 Host 字段
 - Server Port: 服务器端口
 - Document Path: 文档路径，即请求头的请求路径
 - Document Length: 文档长度，即响应头的 Content-Length 字段
 - Concurrency Level: 并发等级，即并发数
 - Time taken for tests: 整个测试花费的时间
 - Complete requests: 完成的请求数
 - Failed request: 失败的请求数
 - Write errors: 写入错误数
 - Total transferred: 传输的字节数
 - HTML transferred: 传输的 HTML 文件的字节数
 - Requests per second: 平均每秒的请求数
 - Time per request: 平均每个请求花费的时间
 - Time per request: 考虑并发，平均每个请求花费的时间
 - Transfer rate: 传输的平均速率
 - Connection Times: 表内描述了连接、处理、等待过程中和整个过程所消耗的最小、平均、中位、最大时间
 - Percentage of the requests served within a certain time:  一定时间内服务了的请求数所占的百分比
