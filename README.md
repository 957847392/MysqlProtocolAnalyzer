# 项目简介
MysqlProtocolAnalyzer 是一个对Mysql的通讯协议的包进行解析的库，纯java编写，输入文件可以是任意的16进制的文本文件，当然需要一定的预处理才能使用。本库是默认处理的是tcpdump产生的16进制的数据文件
## 协议解析
能解析的包有客户端与服务器连接的握手协议的包，所有COM_QUERY类型的语句，COM_STMT_PREPARE和COM_STMT_EXECUTE，还有ok包，以及resultset包等。
是根据官方的http://dev.mysql.com/doc/internals/en/text-protocol.html协议进行解析的。