# Jscrapy

Jscrapy ��һ��javaʵ�ֵķֲ�ʽ����ϵͳ���Ʋ��� �û�ֻ��Ҫ������Ҫץȡ�����ݵ�XPath������д���򣬼�����ʵ�ָ�Ч�ķֲ�ʽ����ϵͳ��
�ƻ�1
 1, ����ʹ�������н���һ������Ŀ
 2, ����ʹ�ô����б����أ�
 3, ����ʹ��cookie�б�
 4, ����ʹ��request head�б�
 5, ��������ʵ�֣�  1, java jdk api ����, 2, apache HttpClient����, 3, ʹ��Python scrapy����, 4, ʹ��Selenium�ű�, 5,ʹ��Oracle Openscript�ű�.
 6, ���Զ�����ȡ�ƻ���
 7, Ԥ����Ĵ洢��ʽ�� txt��Excel��mysql, mongodb, Amazon DB.

�ƻ� 2:
   ������÷��ϵͳ�ķֲ�ʽ��ܣ� apache storm
1, ��÷����Ҫ����hostname��hosts�� ����crontab�Զ�����storm
2, �ͻ�������һ��Topology�� ��������


�ƻ� 3:
   ���ڴ��ͻ����ķֲ�ʽ��ܣ� apache Hadoop
1, ���Բ���YARN����С�
2, �ͻ�������һ��task�� ��������

�ƻ� 4:
  �Ʋ��� Amazon AWS
1, �����Զ�����һ���Ʒ�����
2, �û������ϴ�Jscrapy ��Ŀ�� ������ȡ�ƻ��� �洢��ʽ��
3, ʧ����־����������


Jscrapy is a crawler, which could extract the data from internet.
Plan 1:
 1, could run "jscrapy init" to generate a new project;
 2, could read proxy from a ip list file;;
 3, could read cookie list from a list file;
 4, could read request head from a file;
 5, could custom download implement; 1, jdk httpdownload, 2, apache HttpClient, 3, Python scrapy , 4, Selenium, 5, Openscript.
 6, could define scrawler plan.
 7, store format�� txt��Excel��mysql, mongodb, Amazon DB.

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


