系统描述
    使用C++实现， 运行在Linux下， 依赖mysqlclient库, 消息的编解码使用protobuf。
    客户端与服务器的通信采用TCP长连接。 服务器采用多线程异步模型，主线程接收新连接，
    子线程通过事件循环处理网络IO。
体系结构
  
