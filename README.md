无人机程序使用说明
=====
1.将项目解压后导入您熟悉的IDE，入IDEA、Eclipse等。

2.找到Plane类的主函数，其中项目已存在数据文件并且默认定义了要读取的文件路径 "src/main/resources/data.txt" ， 您可以将此路径改成自己需要读取的文件路径。

3.启动main函数程序即启动，根据打印台信息引导您输入正确的消息id，即可查看结果信息。

4.若无人机出现故障将自动打印日志到logger.log文件方便用户查看问题。

温馨提示：输出消息id时不要输入其它字符或者负数，如果是负数程序自动结束。