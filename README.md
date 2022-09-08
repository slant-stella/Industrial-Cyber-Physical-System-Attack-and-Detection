# Industrial-Cyber-Physical-System-Attack-and-Detection
PLC攻击大全介绍：https://mp.weixin.qq.com/s/o6Dr93Jpc66tw_1Q6eSD1A

S7comm协议解析：https://www.likecs.com/show-94470.html

针对攻击者实施内部攻击之前易出现的通过外部网络渗透到工业信息系统内网主机（如操作员站等）进行非法操作，进行研究和分析，例如远程操控（Remote to login，R2L）、越权（User to root，U2R）类渗透性攻击，此类嵌入型渗透攻击隐蔽性强，识别难度高，但若一旦从数据包检测中发现即可阻止其进行内部攻击（如虚假数据注入攻击，功能码修改攻击），可以达到早发现早隔离，需要发掘一种既可保证较高正常攻击类识别率的基础上，最大程度提高对R2L 和U2R 攻击类的检测准确率的方法。

(1) 本地用户越权攻击（User to Root attack，U2R）：是一种典型的越权攻击，指攻击者通过以无权限或权限较低的用户身份避免验证操作或利用系统漏洞直接获取root 权限，从而登陆进行非法数据盗取，查阅以及实时监控；

(2) 远程操控攻击（Remote to Login attack，R2L）：是一种远程用户攻击，通常指本地系统缺少用户密码管理工作导致恶意者可以远程登陆计算机进行非法操作。

<!-- ![image](Images/v2-4a7d54afb651ad8bf9bee8888c1e5d12_1440w.jpg) -->


<div align=center><img src="Images/v2-4a7d54afb651ad8bf9bee8888c1e5d12_1440w.jpg" width="  " ></div>
