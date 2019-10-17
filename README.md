综述：互联网审查检测 —— 翻译by吴佳挺

 

作者：Giuseppe Aceto1),Antonio Pescapé1) *

    1): University of Naples Federico II | UNINA · Department of Electrical Engineering and Information Technology.

单位：University of Napoli Federico II, Italy

发表：Computer Networks, 2015

页数：41页

引用：160篇文献

        上周末翻译了一篇关于互联网审查检测的综述文章。该文章首先介绍了审查技术的各种阻断方式。然后，根据各种阻断方式，介绍了相应的审查检测方法。再介绍现行的各种审查检测架构、方法、工具和平台。这篇综述参考了160篇文章，篇幅较长，覆盖全面，但缺点是不够细致，是互联网审查领域较好的参考资料。



目录

1.    介绍和动机
2.    背景：互联网审查的技术方面和定义
2.1．定义
2.2．基于客户的审查
2.3.基于服务器的审查
2.4．基于网络的审查
2.5．其他相关概念
2.5.1．自我审查
2.5.2．规避
3.    审查技术
3.1．BGP篡改
3.2.DNS篡改
3.2.1．DNS劫持
3.2.2．DNS注入
3.2.3．DNS-Sec DoS
3.4． TCP连接中断
3.5．软审查
3.6． TLS篡改
3.6.1． TLS强制认证创建攻击
3.6.2． TLS DoS
3.7关键字封锁
3.8 HTTP篡改
3.9 HTTP代理过滤
3.10多级阻塞
3.10.1 BGP劫持+ HTTP代理
3.10.2 DNS劫持+ HTTP代理
3.10.3关键字拦截+ TCP中断
4.    审查检测技术和体系结构
4.1主动检测方法
4.1.1 DNS解析
4.1.2 IP可达性
4.1.3 TCP可达性
4.1.4 HTTP篡改
4.1.5 TLS篡改
4.1.6检测检查设备
4.1.7软审查检测
4.1.8检测基于服务器的审查
4.2被动检测方法
4.2.1基于服务器的检测
4.2.2基于网关的检测
4.3检测架构
4.3.1  ConceptDoppler
4.3.2 MOR
4.3.3  CensMon
4.3.4 UBICA
4.3.5 WCMT
5.    审查制度检测平台和工具
5.1 rTurtle
5.2 Herdict
5.3 Alkasir
5.4 YouTomb
5.5  Greatfire.org
5.6 OONI
5.7  Weiboscope
5.8 Samizdat
5.9  Spookyscan
5.10 encore
5.11其他诊断工具
6.    审查检测架构，工具和平台的特征
6.1  Complexity
6.2 Probe
6.3控制
6.4部署方式
6.5目标选择
6.6证据收集与分析
6.7  Reporting
7.    讨论与结论
7.1 挑战和总结
7.1.1 审查分析的挑战
7.1.2 审查制度的挑战
References