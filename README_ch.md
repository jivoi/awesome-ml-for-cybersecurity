# 网络安全中机器学习大合集 [![Awesom](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://github.com/jivoi/awesome-ml-for-cybersecurity/raw/master/cyber-ml-logo.png" align="right" width="100">](https://github.com/jivoi/awesome-ml-for-cybersecurity)

历年来那些与网络安全中机器学习相关最好的工具与资源

## 目录

 - [数据集](#-datasets)
 - [论文](#-papers)
 - [书籍](#-books)
 - [演讲](#-talks)
 - [教程](#-tutorials)
 - [课程](#-courses)
 - [杂项](#-miscellaneous)

## [↑](#table-of-contents) 贡献

如果你想要添加工具或资源请参阅 [CONTRIBUTING](./CONTRIBUTING.md)

## [↑](#table-of-contents) 数据集

* [安全相关数据样本集](http://www.secrepo.com/)
* [DARPA 入侵检测数据集](https://www.ll.mit.edu/ideval/data/)
* [Stratosphere IPS 数据集](https://stratosphereips.org/category/dataset.html)
* [开放数据集](http://csr.lanl.gov/data/)
* [NSA 的数据捕获](http://www.westpoint.edu/crc/SitePages/DataSets.aspx)
* [ADFA 入侵检测数据集](https://www.unsw.adfa.edu.au/australian-centre-for-cyber-security/cybersecurity/ADFA-IDS-Datasets/)
* [NSL-KDD 数据集](https://github.com/defcom17/NSL_KDD)
* [恶意 URL 数据集](http://sysnet.ucsd.edu/projects/url/)
* [多源安全事件数据集](http://csr.lanl.gov/data/cyber1/)
* [恶意软件训练集](http://marcoramilli.blogspot.cz/2016/12/malware-training-sets-machine-learning.html)
* [KDD Cup 1999 数据集](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
* [Web 攻击载荷](https://github.com/foospidy/payloads)
* [WAF 恶意请求数据集](https://github.com/faizann24/Fwaf-Machine-Learning-driven-Web-Application-Firewall)
* [恶意软件训练数据集](https://github.com/marcoramilli/MalwareTrainingSets)
* [Aktaion 数据集](https://github.com/jzadeh/Aktaion/tree/master/data)
* [DeepEnd 研究中的犯罪数据集](https://www.dropbox.com/sh/7fo4efxhpenexqp/AADHnRKtL6qdzCdRlPmJpS8Aa/CRIME?dl=0)
* [公开可用的 PCAP 文件数据集](http://www.netresec.com/?page=PcapFiles)

## [↑](#table-of-contents) 论文

* [快速、可靠、准确：使用神经网络建模猜测密码](https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/melicher)
* [封闭世界之外，应用机器学习在网络入侵检测](http://ieeexplore.ieee.org/document/5504793/?reload=true)
* [基于 Payload 的异常网络入侵检测](https://link.springer.com/chapter/10.1007/978-3-540-30143-1_11)
* [使用元数据与结构特征检测恶意 PDF](http://dl.acm.org/citation.cfm?id=2420987)
* [对抗性支持向量机学习](https://dl.acm.org/citation.cfm?id=2339697)
* [利用机器学习颠覆垃圾邮件过滤器](https://dl.acm.org/citation.cfm?id=1387709.1387716)
* [CAMP – 内容不可知的恶意软件保护](http://www.covert.io/research-papers/security/CAMP%20-%20Content%20Agnostic%20Malware%20Protection.pdf)
* [Notos – 构建动态 DNS 信誉系统](http://www.covert.io/research-papers/security/Notos%20-%20Building%20a%20dynamic%20reputation%20system%20for%20dns.pdf)
* [Kopis – 在 DNS 上层结构中检测恶意软件的域名](http://www.covert.io/research-papers/security/Kopis%20-%20Detecting%20malware%20domains%20at%20the%20upper%20dns%20hierarchy.pdf)
* [Pleiades – 检测基于 DGA 的恶意软件的崛起](http://www.covert.io/research-papers/security/From%20throw-away%20traffic%20to%20bots%20-%20detecting%20the%20rise%20of%20dga-based%20malware.pdf)
* [EXPOSURE – 使用被动 DNS 分析找到恶意域名](http://www.covert.io/research-papers/security/Exposure%20-%20Finding%20malicious%20domains%20using%20passive%20dns%20analysis.pdf)
* [Polonium – 恶意软件检测中万亿级图计算挖掘](http://www.covert.io/research-papers/security/Polonium%20-%20Tera-Scale%20Graph%20Mining%20for%20Malware%20Detection.pdf)
* [Nazca – 在大规模网络中检测恶意软件分布](http://www.covert.io/research-papers/security/Nazca%20-%20%20Detecting%20Malware%20Distribution%20in%20Large-Scale%20Networks.pdf)
* [PAYL – 基于 Payload 的网络异常入侵检测](http://www.covert.io/research-papers/security/PAYL%20-%20Anomalous%20Payload-based%20Network%20Intrusion%20Detection.pdf)
* [Anagram – 用于对抗模仿攻击的内容异常检测](http://www.covert.io/research-papers/security/Anagram%20-%20A%20Content%20Anomaly%20Detector%20Resistant%20to%20Mimicry%20Attack.pdf)
* [在网络安全中应用机器学习](https://www.researchgate.net/publication/283083699_Applications_of_Machine_Learning_in_Cyber_Security)
* [用数据挖掘构建网络入侵检测系统(RUS)](http://vak.ed.gov.ru/az/server/php/filer.php?table=att_case&fld=autoref&key%5B%5D=100003407)
* [数据挖掘在企业网络中构建入侵检测系统 (RUS)](http://engjournal.ru/articles/987/987.pdf)
* [应用神经网络在计算机安全任务分层 (RUS)](http://engjournal.ru/articles/534/534.pdf)
* [数据挖掘技术与入侵检测 (RUS)](http://vestnik.sibsutis.ru/uploads/1459329553_3576.pdf)
* [网络入侵检测系统中的降维](http://elib.bsu.by/bitstream/123456789/120105/1/v17no3p284.pdf)

## [↑](#table-of-contents) 书籍

* [网络安全中的数据挖掘与机器学习](https://www.amazon.com/Data-Mining-Machine-Learning-Cybersecurity/dp/1439839425)
* [网络安全中的机器学习与数据挖掘](https://www.amazon.com/Machine-Learning-Mining-Computer-Security/dp/184628029X)
* [网络异常检测：机器学习观点](https://www.amazon.com/Network-Anomaly-Detection-Learning-Perspective/dp/1466582081)

## [↑](#table-of-contents) 演讲

* [应用机器学习来支撑信息安全](https://www.youtube.com/watch?v=tukidI5vuBs)
* [利用不完整的信息进行网络防卫](https://www.youtube.com/watch?v=36IT9VgGr0g)
* [机器学习应用于网络安全监测](https://www.youtube.com/watch?v=vy-jpFpm1AU)
* [测量你威胁情报订阅的 IQ](https://www.youtube.com/watch?v=yG6QlHOAWiE)
* [数据驱动的威胁情报：指标的传播与共享的度量](https://www.youtube.com/watch?v=6JMEKnes-w0)
* [机器学习应对数据盗窃与其他主题](https://www.youtube.com/watch?v=dGwH7m4N8DE)
* [基于机器学习监控的深度探索](https://www.youtube.com/watch?v=TYVCVzEJhhQ)
* [Pwning 深度学习系统](https://www.youtube.com/watch?v=JAGDpJFFM2A)
* [社会工程学中武器化的数据科学](https://www.youtube.com/watch?v=l7U0pDcsKLg)
* [打败机器学习，你的安全厂商没告诉你的事儿](https://www.youtube.com/watch?v=oiuS1DyFNd8)
* [集思广益，群体训练-恶意软件检测的机器学习模型](https://www.youtube.com/watch?v=u6a7afsD39A)
* [打败机器学习，检测恶意软件的系统缺陷](https://www.youtube.com/watch?v=sPtbDUJjhbk)
* [数据包捕获 – 如何使用机器学习发现恶意软件](https://www.youtube.com/watch?v=2cQRSPFSY-s)
* [五分钟用机器学习构建反病毒软件](https://www.youtube.com/watch?v=iLNHVwSu9EA&t=245s)
* [使用机器学习狩猎恶意软件](https://www.youtube.com/watch?v=zT-4zdtvR30)
* [机器学习应用于威胁检测](https://www.youtube.com/watch?v=qVwktOa-F34)
* [机器学习与云：扰乱检测与防御](https://www.youtube.com/watch?v=fRklX97iGIw)
* [在欺诈检测中应用机器学习与深度学习](https://www.youtube.com/watch?v=gHtN4jU69W0)
* [深度学习在流量识别上的应用](https://www.youtube.com/watch?v=B7OKgC3AJVM)
* [利用不完整信息进行网络防卫：机器学习方法](https://www.youtube.com/watch?v=_0CRSF6yPB4)
* [机器学习与数据科学](https://vimeo.com/112702666)
* [云计算规模的机器学习应用于网络防御的进展](https://www.youtube.com/watch?v=skSIIvvZFIk)
* [应用机器学习：打败现代恶意文档](https://www.youtube.com/watch?v=ZAuCEgA3itI)
* [使用机器学习与 GPO 自动防御勒索软件](https://www.rsaconference.com/writable/presentations/file_upload/spo2-t11_automated-prevention-of-ransomware-with-machine-learning-and-gpos.pdf)
* [通过挖掘安全文献检测恶意软件](https://www.usenix.org/conference/enigma2017/conference-program/presentation/dumitras)

## [↑](#table-of-contents) 教程

* [点击安全数据窃听项目](http://clicksecurity.github.io/data_hacking/)
* [使用神经网络生成人类可读的密码](http://fsecurify.com/using-neural-networks-to-generate-human-readable-passwords/)
* [基于机器学习的密码强度分类](http://fsecurify.com/machine-learning-based-password-strength-checking/)
* [应用机器学习在检测恶意 URL](http://fsecurify.com/using-machine-learning-detect-malicious-urls/)
* [在安全与欺诈检测中的大数据与数据科学](http://www.kdnuggets.com/2015/12/big-data-science-security-fraud-detection.html)
* [使用深度学习突破验证码](https://deepmlblog.wordpress.com/2016/01/03/how-to-break-a-captcha-system/)
* [网络安全与入侵检测中的数据挖掘](https://www.r-bloggers.com/data-mining-for-network-security-and-intrusion-detection/)
* [机器学习应用于网络安全与威胁狩猎简介](http://blog.sqrrl.com/an-introduction-to-machine-learning-for-cybersecurity-and-threat-hunting)
* [应用机器学习提高入侵检测系统](https://securityintelligence.com/applying-machine-learning-to-improve-your-intrusion-detection-system/)
* [使用 Suricata 与机器学习分析僵尸网络](http://blogs.splunk.com/2017/01/30/analyzing-botnets-with-suricata-machine-learning/)
* [fWaf – 机器学习驱动的 Web 应用防火墙](http://fsecurify.com/fwaf-machine-learning-driven-web-application-firewall/)
* [网络安全中的深度域学习](https://blog.cyberreboot.org/deep-session-learning-for-cyber-security-e7c0f6804b81#.eo2m4alid)

## [↑](#table-of-contents) 课程

* [Stanford 的网络安全数据挖掘课](http://web.stanford.edu/class/cs259d/)
* [Infosec 数据科学与机器学习](http://www.pentesteracademy.com/course?id=30)

## [↑](#table-of-contents) 杂项

* [使用人类专家的输入对网络攻击达到 85% 的预测系统](http://news.mit.edu/2016/ai-system-predicts-85-percent-cyber-attacks-using-input-human-experts-0418)
* [使用机器学习的网络安全项目开源列表](http://www.mlsecproject.org/#open-source-projects)

## 许可证

![cc license](http://i.creativecommons.org/l/by-sa/4.0/88x31.png)

许可证为 [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/)




