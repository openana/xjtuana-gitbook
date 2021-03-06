# STU 无线

## 使用方法

1. 连接名称为 STU 的无线网络。

2. 浏览器应该会自动弹出登录页面，若未自动弹出，可手动打开浏览器，在地址栏输入 **`10.6.11.8`** 后确认。

3. 选择相对应的套餐：校园网、中国移动、中国联通、中国电信，并且输入相对应套餐的账号密码点击登录。

![](../.gitbook/assets/image%20%284%29.png)

![](../.gitbook/assets/image%20%282%29.png)

4. 登录成功后，如果想下线本设备，浏览器登录 **`10.6.11.8`** ，点击断开链接即可。  
  


![](../.gitbook/assets/image%20%281%29.png)

5. 如果想查看本账号在线终端，浏览器登录**`10.6.11.8`** ，显示在线会话即可。



![](../.gitbook/assets/image%20%283%29.png)

![](../.gitbook/assets/image%20%288%29.png)

6. 认证采用无感知认证，一次认证后，后续再连接网络无需认证（前提是没有点击断开链接），可以在**`10.6.11.8`** 查看无感知信息。



![](../.gitbook/assets/image%20%285%29.png)

![](../.gitbook/assets/image%20%287%29.png)

##  网络拓扑

1. 无线网络架构采用二层网络架构，用户网关在 BRAS 设备上
2. 认证采用 WeNet AAA 认证服务器进行 IPOE WEB 认证
3. 出口采用防火墙连接三家运营商线路
4. 校园网流量使用学校教育网出口



![STU &#x7F51;&#x7EDC;&#x62D3;&#x6251;](../.gitbook/assets/image%20%286%29.png)

## 相关文件

### 技术资料

{% file src="../.gitbook/assets/stu-shi-yong-fang-fa-wu-xian-tuo-pu-.docx" %}

{% file src="../.gitbook/assets/h3c-wa6320h-shi-nei-mian-ban-xing-wu-xian-jie-ru-she-bei-chan-pin-cai-ye-.pdf" %}



