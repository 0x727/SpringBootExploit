<h1 align="center" >SpringBootExploit</h1>
<h3 align="center" >一款针对SpringBootEnv页面进行快速漏洞利用</h3>
 <p align="center">
    <a href="https://github.com/0x727/SpringBootExploit"></a>
    <a href="https://github.com/0x727/SpringBootExploit"><img alt="SpringBootExploit" src="https://img.shields.io/badge/SpringBootExploit-green"></a>
    <a href="https://github.com/0x727/SpringBootExploit"><img alt="Forks" src="https://img.shields.io/github/forks/0x727/SpringBootExploit"></a>
     <a href="https://github.com/0x727/SpringBootExploit"><img alt="Release" src="https://img.shields.io/github/release/0x727/SpringBootExploit.svg"></a>
  <a href="https://github.com/0x727/SpringBootExploit"><img alt="Stars" src="https://img.shields.io/github/stars/0x727/SpringBootExploit.svg?style=social&label=Stars"></a>
     <a href="https://github.com/SummerSec"><img alt="Follower" src="https://img.shields.io/github/followers/SummerSec.svg?style=social&label=Follow"></a>
     <a href="https://github.com/SummerSec"><img alt="Visitor" src="https://visitor-badge.laobi.icu/badge?page_id=SummerSec.SpringBootExploit"></a>
	<a href="https://twitter.com/SecSummers"><img alt="SecSummers" src="https://img.shields.io/twitter/follow/SecSummers.svg"></a>
	<a xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="https://visitor-badge.laobi.icu"><rect fill="rgba(0,0,0,0)" height="20" width="49.6"/></a>
	<a xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xlink:href="https://visitor-badge.laobi.icu"><rect fill="rgba(0,0,0,0)" height="20" width="17.0" x="49.6"/></a>
	</p>





## 📝 TODO

* 支持Eureka XStream deserialization RCE
* 支持Fastjson 内存马注入
* 支持更多可以使用JNDI内存马注入反序列化漏洞
* 支持内存马路径和密码修改

........




----

## :dragon:来龙去脉

项目是根据[Spring Boot Vulnerability Exploit Check List](https://github.com/LandGrey/SpringBootVulExploit)清单编写，目的hvv期间快速利用漏洞、降低漏洞利用门槛。



----



##  :zap: 下载安装

1. 从[releases](https://github.com/0x727/SpringBootExploit/releases)下载最新版Spring Boot Exploit压缩包，配合[JNDIExploit](https://github.com/0x727/JNDIExploit)使用。（:star:推荐）
2. 
    1. git clone https://github.com/0x727/SpringBootExploit 
    2. git clone https://github.com/0x727/JNDIExploit （目前不对外开放）
    3. mvn clean package -DskipTests 分别打SpringBootExploit包和JNDIExploit



----

## :clapper:使用方法

1. 首先在服务器上上传打包好的JNDIExploit工具，解压。使用命令启动java -jar JNDIExploit-1.2-SNAPSHOT.jar 
2. 输入目标地址和配置服务器地址，点击连接。出现如下图所示代表连接成功。



![image](https://user-images.githubusercontent.com/47944478/200214227-e6c61ef1-6068-4553-a083-0c2d203591b1.png)

3. 漏洞利用

    建议首先点击检测环境，会自动判断是否存在漏洞。漏洞验证方法是Check list的方法，如果有更好的方法可以提交工单会考虑添加。

    ![image](https://user-images.githubusercontent.com/47944478/200214192-796332cf-fd56-4f30-b624-e17d2137aa8c.png)


    4. 漏洞利用，目前只支持内存马注入

    ![image-20210812110245884](https://gitee.com/samny/images/raw/master/summersec//45u02er45ec/45u02er45ec.png)
![image](https://user-images.githubusercontent.com/47944478/200214251-03571a05-ae55-47be-88b6-00cd5de4a737.png)





---

## :b:免责声明

该工具仅用于安全自查检测

由于传播、利用此工具所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。

本人拥有对此工具的修改和解释权。未经网络安全部门及相关部门允许，不得善自使用本工具进行任何攻击活动，不得以任何方式将其用于商业目的。



----



## :book: 参考项目

https://github.com/woodpecker-appstore/springboot-vuldb



---

![as](https://starchart.cc/0x727/SpringBootExploit.svg)

