# <img src="images/logo_maxkey.png?raw=true"  width="200px"   alt=""/>


<a href="README_en.md" target="_blank"><b>English</b></a>  |  <a href="README_zh.md" target="_blank"><b>中文</b></a>

# 概述

<b>MaxKey(马克思的钥匙)</b>单点登录认证系统(Single Sign On System)，寓意是最大钥匙,是<b>业界领先的企业级开源IAM身份管理和身份认证产品</b>,支持OAuth 2.0/OpenID Connect、SAML 2.0、JWT、CAS、SCIM等标准协议，提供<b>简单、标准、安全和开放</b>的用户身份管理(IDM)、身份认证(AM)、单点登录(SSO)、RBAC权限管理和资源管理等。

官方网站  <a href="https://www.maxkey.top" target="_blank"><b>官网</b></a> |  <a href="https://maxkeytop.gitee.io" target="_blank"><b>官网二线</b></a>

QQ交流群：<b>434469201</b> 

邮箱email: <b>maxkeysupport@163.com</b>

代码托管 <a href="https://github.com/MaxKeyTop/MaxKey" target="_blank"><b>GitHub</b></a> | <a href="https://gitee.com/maxkeytop/MaxKey" target="_blank"><b>码云(Gitee)</b></a>

 
什么是<b>单点登录(Single Sign On）</b>，简称为<b>SSO</b>？

用户只需要登录认证中心一次就可以访问所有相互信任的应用系统，无需再次登录。
  
主要功能： 

1) 所有应用系统共享一个身份认证系统

2) 所有应用系统能够识别和提取ticket信息
 
 
# 产品特性

1.  标准认证协议：

| 序号    | 协议   |  支持  |
| --------| :-----  | :----:  |
| 1.1     | OAuth 2.0/OpenID Connect   |  高  |
| 1.2     | SAML 2.0   				 |  高  |
| 1.3     | JWT  					     |  高  |
| 1.4     | CAS						 |  高  |
| 1.5     | FormBased				     |  中  |
| 1.6     | TokenBased(Post/Cookie)    |  中  |
| 1.7     | ExtendApi				     |  低  |
| 1.8     | EXT						 |  低  |

2. 登录支持

| 序号    | 登录方式   | 
| --------| :-----  |
| 2.1     | 动态验证码  字母/数字/算术 	| 
| 2.2     | 双因素认证   	| 
| 2.3     | 短信认证  腾讯云短信/阿里云短信/网易云信 	|
| 2.4     | 登录易/Google/Microsoft Authenticator/FreeOTP/支持TOTP或者HOTP |
| 2.5     | Kerberos/SPNEGO/AD域|
| 2.6     | 社交账号 微信/QQ/微博/钉钉/Google/Facebook/其他  | 


3. 提供标准的认证接口以便于其他应用集成SSO，安全的移动接入，安全的API、第三方认证和互联网认证的整合。

4. 提供用户生命周期管理，支持SCIM 2协议，基于Apache Kafka代理，通过连接器(Connector)实现身份供给同步。

5. 认证中心具有平台无关性、环境多样性，支持Web、手机、移动设备等, 如Apple iOS，Andriod等，将认证能力从B/S到移动应用全面覆盖。

6. 多种认证机制并存，各应用系统可保留原有认证机制，同时集成认证中心的认证；应用具有高度独立性，不依赖认证中心，又可用使用认证中心的认证，实现单点登录。

7. 基于Java平台开发，采用Spring、MySQL、Tomcat、Apache Kafka、Redis等开源技术，支持微服务，扩展性强。  

8. 开源、安全、自主可控，许可证 Apache 2.0 License & <a href="https://maxkey.top/zh/about/licenses.html" target="_blank">MaxKey版权声明</a>。 


# 界面

**MaxKey认证**

登录界面
<img src="images/maxkey_login.png?raw=true"/>

主界面
<img src="images/maxkey_index.png?raw=true"/>

**MaxKey管理**

访问报表
<img src="images/maxkey_mgt_rpt.png?raw=true"/>

用户管理
<img src="images/maxkey_mgt_users.png?raw=true"/>

应用管理
<img src="images/maxkey_mgt_apps.png?raw=true"/>


# 下载

当前版本百度网盘下载,<a href="https://maxkey.top/zh/about/download.html" target="_blank"> 历史版本</a>
| 版本    | 日期   |  下载地址  |  提取码  |
| --------| :-----  | :----  | :----:  |
| v 2.4.0 RC | 2020/12/15   |  <a href="https://pan.baidu.com/s/1xUZZJrxEUmbU3thIxd2lDA" target="_blank">链接下载</a>  |  **k65z**  |


# Roadmap

1.零信任场景整合

2.MaxKey Cloud(微服务版)-2021年


