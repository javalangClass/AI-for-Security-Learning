# AI-for-Security-Learning
安全场景、基于AI的安全算法和安全数据分析学习笔记（工程类学习笔记，不包含论文、书籍、视频等，不花里胡哨嘻嘻哈哈）

项目地址：https://github.com/404notf0und/AI-for-Security-Learning

最近更新日期为：2018/1/9

新增：
- [阿里巴巴直播内容风险防控中的AI力量](https://zhuanlan.zhihu.com/p/24690287)
- [NLP机器学习模型安全性及实践](https://bbs.pediy.com/thread-230125.htm)
- [对深度学习的降维攻击 — 人工智能系统数据流中的安全风险](https://www.anquanke.com/post/id/95095)
- [DEFCON CHINA议题解读 | 对深度学习系统的数据流攻击](https://www.anquanke.com/post/id/144837)
- [机器学习对抗性攻击报告](https://mp.weixin.qq.com/s/QKXd9AKkVwk3CO45-BbZSA?)
- [机器学习实践-DGA检测](http://galaxylab.org/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E5%AE%9E%E8%B7%B5-dga%E6%A3%80%E6%B5%8B/)
- [用机器学习进行恶意软件检测——以阿里云恶意软件检测比赛为例](https://xz.aliyun.com/t/3704)
- [第二届微软恶意软件预测挑战赛初探](http://4o4notfound.org/index.php/archives/179/)

同步更新于：[404 Not Found：AI for Security](http://www.4o4notfound.org)

目录：
- [防护篇](#防护篇)
	- [使用AI保护应用](#使用AI保护应用)
		- [恶意软件和代码](#恶意软件和代码)
		- [恶意流量检测](#恶意流量检测)
		- [域名安全检测](#域名安全)
		- [业务安全检测](#业务安全)
		- [Web安全检测](#Web安全)
			- [URL异常检测](#Web安全之URL异常检测)
			- [XSS检测](#Web安全之XSS检测)
			- [Web攻击多分类检测](#Web安全之攻击多分类检测)
			- [Webshell检测](#Web安全之Webshell检测)
			- [Other](#Web安全之其他)
		- [杂项](#杂项)
			- WindowsRDP检测
			- PowerShell检测
			- 用户行为(UBA)检测
			- 弱口令检测
			- 安全运营
	- [(使用AI)保护AI(框架、数据、模型、系统)](#保护AI)
- [对抗篇](#对抗篇)
	- [使用AI攻击应用](#使用AI攻击应用)
	- [(使用AI)攻击AI(框架、数据、模型、系统)](#攻击AI)
		- [攻击AI框架](#攻击AI框架)
		- [攻击AI模型](#攻击AI模型)
<!-- more -->

# 防护篇 #
## 使用AI保护应用 ##
### 恶意软件和代码 ###
- [深度学习在恶意软件检测中的应用](https://xz.aliyun.com/t/2447)
- [恶意软件与数据分析](https://iami.xyz/AliSEC3/)
- [利用机器学习进行恶意代码分类](http://drops.xmd5.com/static/drops/tips-8151.html)
- [用机器学习检测Android恶意代码](http://drops.xmd5.com/static/drops/mobile-13428.html)
- [Malware Detection in Executables Using Neural Networks](https://devblogs.nvidia.com/malware-detection-neural-networks/)
- [基于深度学习的恶意样本行为检测(含源码)](https://www.freebuf.com/articles/system/182566.html)
- [用机器学习进行恶意软件检测——以阿里云恶意软件检测比赛为例](https://xz.aliyun.com/t/3704)
- [第二届微软恶意软件预测挑战赛初探](http://4o4notfound.org/index.php/archives/179/)

### 恶意流量检测 ###
- [利用机器学习检测HTTP恶意外连流量](https://www.freebuf.com/column/170483.html)

### 域名安全检测 ###
- [使用fasttext进行DGA检测](https://iami.xyz/DGA-Detect/)
- [机器学习实践-DGA检测](http://galaxylab.org/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E5%AE%9E%E8%B7%B5-dga%E6%A3%80%E6%B5%8B/)
- [使用CNN检测DNS隧道](https://github.com/BoneLee/dns_tunnel_dectect_with_CNN)
- [机器学习与威胁情报的融合：一种基于AI检测恶意域名的方法](https://www.freebuf.com/articles/es/187451.html)

### 业务安全检测 ###
- [基于设备指纹的风控建模以及机器学习的尝试](https://xz.aliyun.com/t/2801)
- [如何在安全风控中评估和量化机器学习有效性](https://xz.aliyun.com/t/2951)
- [人工智能反欺诈三部曲——特征工程](https://www.anquanke.com/post/id/85741)
- [阿里巴巴直播内容风险防控中的AI力量](https://zhuanlan.zhihu.com/p/24690287)

### Web安全检测 ###
### Web安全之URL异常检测 ###
- [基于机器学习的web异常检测](https://www.freebuf.com/articles/web/126543.html)
- [基于大数据和机器学习的Web异常参数检测系统Demo实现](https://www.freebuf.com/articles/web/134334.html)
- [基于机器学习的web应用防火墙](https://github.com/faizann24/Fwaf-Machine-Learning-driven-Web-Application-Firewall)
- [LSTM识别恶意HTTP请求](https://www.cdxy.me/?p=775)
- [基于URL异常检测的机器学习模型mini部署](http://4o4notfound.org/index.php/archives/84/)
- [我的AI安全检测学习笔记（一）](http://4o4notfound.org/index.php/archives/127/)

### Web安全之XSS检测 ###
- [机器学习识别XSS实践](https://www.cdxy.me/?p=773)
- [使用深度学习检测XSS](http://webber.tech/posts/%E4%BD%BF%E7%94%A8%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E6%A3%80%E6%B5%8BXSS/)
- [使用深度学习检测XSS(续)](http://webber.tech/posts/%E4%BD%BF%E7%94%A8%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E6%A3%80%E6%B5%8BXSS%28%E7%BB%AD%29/)

### Web安全之攻击多分类检测 ###
- [基于机器学习的WEB攻击分类检测模型](https://www.freebuf.com/news/184687.html)
- [基于机器学习的攻击检测系统](https://www.freebuf.com/column/189981.html)

### Web安全之Webshell检测 ###
- [基于机器学习的分布式webshell检测系统-特征工程（1）](https://www.s0nnet.com/archives/fshell-feature-1)
- [深度学习PHP webshell查杀引擎demo](https://www.cdxy.me/?p=788)
- [使用机器学习识别WebShell](https://github.com/lcatro/WebShell-Detect-By-Machine-Learning)
- [基于机器学习的分布式Webshell检测系统](https://github.com/Lingerhk/fshell)
- [GitChat · 安全 | 基于机器学习的 Webshell 发现技术探索](http://blog.csdn.net/GitChat/article/details/77932384?locationNum=4&fps=1)
- [刘焱： Webshell 发现技术实战解析](http://gitbook.cn/books/5964d154cc597d3e0c08667c/index.html)
- [安普诺张涛：再谈webshell检测](http://www.cnetsec.com/article/22593.html)
- [新开始:webshell的检测](https://iami.xyz/New-Begin-For-Nothing/)
- [基于机器学习的WebShell检测方法与实现(上)](https://www.freebuf.com/articles/web/181169.html)

### Web安全之其他 ###
- [Web安全检测中机器学习的经验之谈](https://iami.xyz/ML-IN-Webshell-Detection-Advantages-And-Disadvantages/)

### 杂项 ###
- [机器学习在WindowsRDP版本和后门检测上的应用](https://www.anquanke.com/post/id/157175)
- [用机器学习检测恶意PowerShell](https://xz.aliyun.com/t/2437)
- [机器学习算法在用户行为检测(UBA)领域的应用](http://dearcharles.cn/2017/11/11/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E7%AE%97%E6%B3%95%E5%9C%A8%E7%94%A8%E6%88%B7%E8%A1%8C%E4%B8%BA%E6%A3%80%E6%B5%8B-UBA-%E9%A2%86%E5%9F%9F%E7%9A%84%E5%BA%94%E7%94%A8/)
- [利用机器学习和规则实现弱口令检测](https://manning23.github.io/2018/10/12/%E5%88%A9%E7%94%A8%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E5%92%8C%E8%A7%84%E5%88%99%E5%AE%9E%E7%8E%B0%E5%BC%B1%E5%8F%A3%E4%BB%A4%E6%A3%80%E6%B5%8B/)
- [解决机器学习和安全运营之间的最后一公里问题](https://www.anquanke.com/post/id/163637)

## 保护AI ##
- [如何利用AI对抗“数据污染”和”数据中毒“？](https://www.anquanke.com/post/id/150653)
- [对抗数据中毒--机器学习在阿里巴巴网络安全的应用](https://www.leiphone.com/news/201806/rYrfwtaeCNohEf0D.html)

# 对抗篇 #
## 使用AI攻击应用 ##
- [AI与Android漏洞挖掘的那些事儿](https://www.zybuluo.com/qinyun/note/957067)
- [AI与安全的恩怨情仇五部曲「1」Misuse AI](https://www.zuozuovera.com/archives/1565/)
- [一种基于机器学习的自动化鱼叉式网络钓鱼思路](https://www.freebuf.com/articles/web/132811.html)

## 攻击AI ##
### 攻击AI框架 ###
- [深度学习框架中的魔鬼——探究人工智能系统中的安全问题](https://www.anquanke.com/post/id/86989)
- [对深度学习的降维攻击 — 人工智能系统数据流中的安全风险](https://www.anquanke.com/post/id/95095)
- [DEFCON CHINA议题解读 | 对深度学习系统的数据流攻击](https://www.anquanke.com/post/id/144837)

### 攻击AI模型 ###
- [安全领域中机器学习的对抗和博弈](http://bindog.github.io/blog/2016/11/13/game-playing-with-ml-in-security/)
- [基础攻防场景下的AI对抗样本初探](https://www.cdxy.me/?p=798)
- [机器学习在安全攻防场景的应用与分析](https://www.freebuf.com/articles/neopoints/152457.html)
- [使用生成对抗网络(GAN)生成DGA](http://webber.tech/posts/%E4%BD%BF%E7%94%A8%E7%94%9F%E6%88%90%E5%AF%B9%E6%8A%97%E7%BD%91%E7%BB%9C%28GAN%29%E7%94%9F%E6%88%90DGA/)
- [详解如何使用Keras实现Wassertein GAN](https://mp.weixin.qq.com/s/F2gBP23LCEF72QDlugbBZQ)
- [Is attacking machine learning easier than defending it?](http://www.cleverhans.io/security/privacy/ml/2017/02/15/why-attacking-machine-learning-is-easier-than-defending-it.html)
- [对深度学习的逃逸攻击 ——探究人工智能系统中的安全盲区](https://www.anquanke.com/post/id/87037)
- [NLP机器学习模型安全性及实践](https://bbs.pediy.com/thread-230125.htm)
- [机器学习对抗性攻击报告](https://mp.weixin.qq.com/s/QKXd9AKkVwk3CO45-BbZSA?)

