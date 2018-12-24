# Lanmoyun-download
批量爬取蓝墨云班课中的习题
----
本程序使用Python3.7.0编写

请使用Python3.6及以上版本，若使用低版本请修改toolbox.py下Toolbox类中变量注释
----

安装依赖：


`pip install requests`
  
`pip install lxml`

----

输入账号和密码及待爬取的课程网页即可使用

**请务必查看环境是否需要使用代理！！！**

本程序已构建可执行exe文件

----

待解决问题：

1.将题目以首字母拼音升序排列(拟用pypinyin库构建)
2.改用asyncio + aiohttp + ThreadPoolExecutor进行高并发多线程爬取
