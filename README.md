# Dstar-chinese-Introduction

## D-Star No.1  
无论什么时候，注意你的To指向了正确目标，`Local CQ` `Gateway CQ` `Use Reflector`  `/` `U` `I` `E` 等都代表的是不同的指向。  
确定自己的电台进行了正确的配置。

## D-Star No.2  

使用Dongle的时候（尤其是Pi-Star)，电台要设置`+/-0Mhz`差频，多数Dongle本质上是一个精简的中继+网关，没有差频就没有转发。

## D-Star No.3  

ircDDB.net的Dashboard，或者XLX反射器的D-Star Live页面没有显示我的呼号？  
  
 * 你用了某种版本的Dongle，经测试，部分Pi-Star不会像ircddb.net发送数据。  
 * 你没有设置VIS  ON，解决办法请访问 http://ircddb.net/live-vis.html  或者[这里](网关/ircDDB_live_log.md)。 


## BR2SY 中继台信息

|中继台呼号|中继台协议|下行频率|上行频率|差频|备注|
|---|---|---|---|---|---|
|**BR2SY**|D-Star|439.700.000MHz|434.700.000MHz|-5MHz|---|
|**BR2RSA**|C4FM|439.525.000MHz|434.525.000MHz|-5MHz|---|

### [BR2SY 地理位置](https://aprs.fi/?call=BR2SY-B)
## BR2SY ircDDBGateway 和 XLX207已经正式运行，欢迎广大爱好者连接访问  

BRSY ircDDBGateway 连接方法：  

电台TO编写`BR2SY BL`或者 `/BR2SY B`，按PTT键一次，等待网关回馈。  
收到回馈语音回馈 `Linking to BR2SY B`后将电台TO调整至`Reflector--USE Reflector`  
按PTT键进行通联。

## XLX207反射器介绍：

XLX207可以用REF/DCS/XRF/XLX任意一种协议连接。  
目前XLX207反射器开启A-E模块，A模块互联，B/C模块D-STAR专用，D/E模块用于测试。

XLX207反射器可以支持D-Star/C4FM(YSF)/DMR/P25/NXDN协议通联。  

XLX207不赞成业余无线电爱好者使用商业协议（DMR等协议）通联。  

XLX207不赞成业余无线电爱好者使用具有加密功能的P25协议通联。
