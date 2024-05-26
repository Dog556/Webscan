# Webs-can
Webscan

Webscan--网站存活识别工具 by carrot qq群：611149449
-----------------
安装依赖:pip install -r requirements.txt 

推荐阿里云：pip install -r requirements.txt -i http://mirrors.aliyun.com/pypi/simple/

使用方法 

options:

  -h, --help            show this help message and exit
  
  -f FILE, --file FILE  指定一个txt文档
  
  -t THREAD, --thread THREAD线程最大为10默认
                        
  -c CODE, --code CODE  指定指定状态码，默认为200

常规使用:python webscan.py -r url.txt // url.txt目标地址文件
  
