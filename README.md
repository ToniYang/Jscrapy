# Jscrapy

Jscrapy 是一个java实现的分布式爬虫系统，云部署。
	
用户只需要定义需要抓取的数据的XPath，无需写程序，即可以实现高效的分布式爬虫系统。	 

计划1 

 1, 可以使用命令行建立一个新项目  

 2, 可以使用代理列表下载； 

 3, 可以使用cookie列表； 

 4, 可以使用request head列表； 

 5, 下载器的实现：  1, java jdk api 下载, 2, apache HttpClient下载, 3, 使用Python scrapy下载, 4, 使用Selenium脚本, 5,使用Oracle Openscript脚本.

 6, 可以定义爬取计划。

 7, 预定义的存储格式， txt，Excel，mysql, mongodb, Amazon DB.

计划 2:

   基于树梅派系统的分布式框架， apache storm

1, 树梅派需要设置hostname，hosts。 设置crontab自动启动storm

2, 客户端启动一个Topology， 定义任务。 


计划 3:  
   基于大型机器的分布式框架， apache Hadoop 

1, 可以部署到YARN框架中。  

2, 客户端启动一个task， 定义任务。 

计划 4:  

  云部署 Amazon AWS    

1, 可以自动部署到一个云服务器  

2, 用户可以上传Jscrapy 项目， 定义爬取计划， 存储格式。 

3, 失败日志，报表，报警   


Jscrapy is a crawler, which could extract the data from internet. 

Plan 1:   

 1, could run "jscrapy init" to generate a new project;  

 2, could read proxy from a ip list file;;  

 3, could read cookie list from a list file;  

 4, could read request head from a file;   

 5, could custom download implement; 1, jdk httpdownload, 2, apache HttpClient, 3, Python scrapy , 4, Selenium, 5, Openscript. 		

 6, could define scrawler plan.		

 7, store format： txt，Excel，mysql, mongodb, Amazon DB.		
		
Plan 2:		

 distrubted in mirror system(raspberrypi)		

1, could run in storm system.		

	
Plan 3:		

   distrubted in high performance system(a linux system with men >16G)		

1, could run in hadoop Yarn system.	

Plan 4:  

  could deploy into a cloud system. like Amazon aws.	

1, could auto deploy and run.	

2, could give user a UI to upload Jscrapy project, define scralwer plan and data store format.	

3, failure log, report, warning.


 
