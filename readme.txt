spider_main 爬虫总调度程序
url_manager url 管理器
html_downloader html 下载器
html_parser html 解析器
html_outputer 输出

首先给出目标网址

root_url = "https://baike.baidu.com/item/Python/407313"  #百度百科首地址

创建类目标   obj_spider = SpiderMain()

对目标网址进行爬虫 obj_spider.crawl(root_url)

    if count == 3:                  #total pages
    break
    count += 1
用于设置爬虫需要分析的总页数
