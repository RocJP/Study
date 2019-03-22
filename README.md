# Study-Kali Linux
Kali Linux

 
2.1、被动信息收集
2.2、使用Recon-ng收集信息
2.3、使用Nmap扫描和标识服务
2.4、标识web应用程序防火墙
2.5、确定HTTPS加密参数
2.6、使用浏览器的开发工具分析和更改基本行为
2.7、获取和修改cookie
2.8、利用robots.txt
 
 
 一、信息收集
 1. whois 域名URL               获取注册信息
 2. dig  ns 域名URL              获取域名信息和DNS解析信息  
 3. dig axfr@DNS服务器 域名URL   尝试区域传输攻击来获取服务器解析的所有主机名。
 4.使用theharvester来获取目标网站的邮箱、主机名、IP地址信息。
    # theharvester -b  all  -d  URL
5.使用Netcraft工具           不直接查询服务器获得网站使用的软件版本信息。登陆https://toolbar.netcraft.com/site_report
 6. https://archive.org/web/web.php   这个网站回溯网站以前版本的静态副本
 7.使用谷歌的高级搜索选项 (https://support.google.com/websearch/answer/2466433)
   来查找关于目标域的信息，而无需直接访问它。例如，通过使用site:site_to_look_into“target_domain”
类似这样的搜索，我们可以在最近发现漏洞、泄漏信息或攻击成功的页面中寻找目标域的存在，可以查看以下一些对你有用的网站:
openbugbounty.org：Open Bug Bounty是安全研究人员在面向公众的网站报告和公布漏洞(仅跨站点脚本和跨站点请求伪造)的一个独立站点。所以在谷歌中的搜索将返回所有提到的到“zonetransfe”这是openbugbounty.org所做的。
pastebin.com ：是一种非常普遍的方法，用于让黑客匿名地去过滤和发布攻击期间所获得的信息。
zone-h.org：Zone-H是一个恶意黑客经常去炫耀他们的成就的网站，主要是对网站的破坏。













