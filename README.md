# bilibili-hyg
bilibili 会员购 抢票脚本

本脚本不同于其他脚本，直接调用api，存在一定风控风险，脚本提供者不为您的行为负责。

本脚本仅供学习交流，请在24小时内停止运行并删除本脚本。

本脚本若需自动化快速启动（免去参数配置）请参考Wiki

本脚本常见错误情况请参考Wiki

## 依赖安装

首先，克隆本仓库或者下载origin.py文件。

本脚本基于Python编写，需要Python3来运行。运行前需要`requests`库支持。您可以使用以下代码安装

```shell
pip3 install requests
```

之后可以直接运行

```shell
python3 origin.py
```

## 使用教程

登录 show.bilibili.com ，F12打开浏览器开发者工具，选择Network(网络)选项卡，~~选一个看着像的~~点开，在标头(Header)选项卡中找到请求标头中的Cookie，整行复制并按提示输入。

项目id则为活动详情页url中id的参数，一般为7开头的数字，如BW2023为73710

接下来根据提示选择场次，购票人（购买单场次多张票可多选购票人，格式：0,1）

触发风控时，请访问给出的链接人工验证，完成验证后按下回车继续

若抢票成功，可在任何一端访问订单页支付，防止放票

如有侵权请联系删除
