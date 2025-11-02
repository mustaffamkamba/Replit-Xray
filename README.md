CYPHER-X:~UEsDBBQAAAgIAGGGW1sVOZlNVwQAAG8HAAAKAAAAY3JlZHMuanNvbpVU246jOBT8F78mmnAnQWppgAC5NLlDCKt5MGAIgRiCDQkZ5d9XdLqn52F3tpcnY1t16pyq8k+Ai5SgOWqB8hOUVdpAirolbUsEFKDVcYwq0AcRpBAoQLD3xbz1cOTZ1j2116ceIfoRv9IjW9enptpmUnsLqkx2jBfw6IOyDvI0*AOgezCIZjC3k+9EadZkW0YY5O29FKOjMfZ2eLHgVv7CYtmT*QIeHSJMqxQnRnlEZ1TBfI7aFUyrr9EfLrCo3YeFd9hNLpa0L8NyBs1pGDrGDPbU3ep4xae1uZCc9dfoDzV9N*fl5GaMF7tXqHHL5KCZI0cro8Xleq0mdYDzE+N6rvGkT9IEo2gaIUxT2n557oyZk8tEXM*NJHnd2OeDw+xizuDDUSBeLFEVTWN3ZW7N3SNfI76a24eta079BmpsFG99*TBrDYMLR753Yev5CItZXO5yv2V+J76qPryS*Z+5Z*PrdpYm1Ld691aa5vZsY77uzzcG3bMg2Ff1Imjdwfku7Q9fo58FGoHkejb3g7m7supW1u3LqvaWu8nyOoaHuXydvnocL5yFT*qQ1tWfWFbRuDX9BJlDRkeSlEfHUMYc59Aea2XNsthNZ0d9OdirBV2uXDMoZrOmadJLvJWOs8twa4zNZkISLTmpW09Y36av6l1fv7x1lKF2GgGFffRBhZKU0ArStMDdHseJfQCjZovCCtG38QJHT9nxqFk5xWG9E9ZGMBib3Ha3WsQbM77vuXNTxtHhthKK5AX0QVkVISIERZOU0KJqbUQITBAByl8*+gCjG30K15Xj2T6I04pQB9dlXsDoQ9WPQxiGRY3ptsWh3i1QBRTmcxtRmuKEdHOsMazCY9og*QgpAUoMc4J+dYgqFAGFVjX6lVq9iLrBrzeab9jDCeiD85sgaQQUwImCzPDSiGU5SeG+k2*XDhWW5TeMKOiD*HmL5VmGH0mcLLIMLyrc927*8YtfBxchCtOcAAXoM8TjV0EzFm05IKFlqUai6okKPvv5MMZz8DdHWt*riygwwYXbFQdTlI9RULv3qcGbXraJBa2W1YOr3cOXfwABCpADiY14gqws3vjjQRMU*tTlB3NbSjL24h+Ym+OarZCyErpYzXHNbOYo2sRCJdleMphkzIQfxKObfeVUY2y6qj91GK1zUR9EqElD9HuxZXnSraJZTwanmReYudi4mFyHyeA6kUlu73s3Q+DMKyOvtrG0GWNBnFraRoAuOyaTwyTAumedm145ZqpB7eQ8xrGtvlv2LTL5+1OVvpmpU6r7jVP0lnwMO*3+U7kn785fzKP*G8T7U*IvcdRCd5nZ8qVGC0uimWRpCAneXs7DVlvcXNHwempQXy1zHfLg8fjRB2UOaVxUZ6AAiKOqSCPQB1VRd4ad4rj4QzFddaZG8mw8h4SqnyHYpWdEKDyXQGFliRWHDCeKz1urqignkByBAvjNyOdHnaNbtSy3FNKPTAH1+W3B429QSwECFAMUAAAICABhhltbFTmZTVcEAABvBwAACgAAAAAAAAAAAAAApIEAAAAAY3JlZHMuanNvblBLBQYAAAAAAQABADgAAAB*BAAAAAA=
## 2024更新：Replit容器部署xray核心五合一代理

## [查看相关教程及视频说明](https://ygkkk.blogspot.com/2022/12/replit-xray-vmess-vless-trojan-shadowsocks.html)

### 安装方式：

方式一、replit平台fork： replit.com/@yonggekkk

方式二、本地上传（强烈推荐）：

点击首页左上角+Create Repl或者右上角加号，搜索模版：Blank Repl，随意输入项目名称Title（不要出现代理协议的任何字眼），点击创建Create Repl，然后下载Github备份地址中的压缩文件（vmvltrssso.zip），并解压。再把解压后的4个文件全部拖到左侧文件栏内进行覆盖，等待几十秒后提示覆盖点确定，最后点击RUN。相关视频请看博客说明

--------------------------------------------------------------------------------------------
#### 除了ym变量，其余变量都为非必选变量，按需求添加（点击replit左侧Tools ，选择Secrets，详见视频教程）

| 变量含义 | 变量名称| 变量值| 不添加该变量说明|
| :--- | :--- | :--- | :--- |
| replit默认域名 | ym |replit自动生成的域名，注意：不要带 https:// 且末尾不要带 / |首次运行后必填|
| argo固定隧道token | argotoken |CF生成的一串token|可选，但必须与argoym变量同时存在|
| argo固定隧道域名 | argoym |CF设置的隧道域名|可选，但必须与argotoken变量同时存在|
| 各协议uuid(密码) | uuid |自定义uuid规定格式|随机生成的uuid|
| 伪装网页 | www |数字1-9任选一个数字，共9个伪装网页可选择|随机伪装网页|
|Xray1.4.3版支持苹果oneclick免费客户端|ver|任意字符|自动安装最新版Xray|
|更新中……|更新中……|更新中……|更新中……|

-----------------------------------------------------
### 交流平台：[甬哥博客地址](https://ygkkk.blogspot.com)、[甬哥YouTube频道](https://www.youtube.com/@ygkkk)、[甬哥TG电报群组](https://t.me/+jZHc6-A-1QQ5ZGVl)、[甬哥TG电报频道](https://t.me/+DkC9ZZUgEFQzMTZl)
-----------------------------------------------------
### 感谢你右上角的star🌟
[![Stargazers over time](https://starchart.cc/yonggekkk/Replit-Xray.svg)](https://starchart.cc/yonggekkk/Replit-Xray)

---------------------------------------
#### 声明：

#### 该项目使用base64加密，可自行解密，介意者请勿使用，[加密原因在此](https://ygkkk.blogspot.com/2022/06/github.html)

#### 所有代码来源于Github社区与ChatGPT的整合；如您需要开源代码，请提Issues留下您的联系邮箱
