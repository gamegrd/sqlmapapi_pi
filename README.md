sqlmapapi_pi注入工具
=====
#####本程序利用百度爬取特定的url链接，然后调用sqlmapapi（sqlmap自带的批量接口），进行注入的判断。
#####用法：先在自己sqlmap的目录下执行python sqlmapapi.py -s
进行监听操作。然后执行AutoSqli.py

* 这里要注意的是在代码里自定义搜索关键字：
            key='inurl:asp?id='
* 以及线程数：
            nloops = range(4)   #threads Num
* 建议线程数不要太多，以免卡死。
