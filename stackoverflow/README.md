Requests定时抓取StackOverFlow的问题, 并用Flask框架显示在网页

Requests+XPath负责响应和解析网页
Flask框架负责从MongoDB数据库中读取数据并显示在网页终端
用Linux的crontab命令定时执行抓取网页任务

crontab命令参考

*/1 * * * * /usr/local/bin/python3 /demo.py 

#Python解释器和脚本用绝对路径
