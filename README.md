# 微信红包助手

## 支持微信版本
> **7.0.8**、**7.0.9**、**7.0.10**、**7.0.11**、**7.0.12**、**7.0.13**、**7.0.14**、  
> **7.0.15**、**7.0.16**、**7.0.17**、**7.0.18**、**7.0.19**、**7.0.20**、  
> **8.0.0**、**8.0.1**、**8.0.2**  

## 下载地址
* 百度云盘
> 链接:https://pan.baidu.com/s/1-PpEtqDTzQ4_AdQiQSA5Og  密码:y0hh
* QQ群
> QQ群号码：51204902

## 手机型号及使用的一些说明
* 在使用时一定要在辅助功能（**无障碍**）中找到 **微信红包助手** 这个服务，并将其打开，程序才能正常工作
* 手机在桌面停留不能抢红包请检查手机的通知权限有没有设置
* 接收红包的群请不要开启群消息免打扰，设置显示群成员昵称显示否则可能会出现名称不过滤的BUG
* 名称过滤&红包标题过滤都是模糊匹配，用户的昵称或红包标题包含你所设置的内容就会过滤
* 打开微信通知显示消息详情（微信 设置-新消息提醒-通知显示消息详情）

## 权限要求
* 通知权限
* 浮窗权限
* 读写存储权限
* 后台弹出界面权限（小米、魅族等）

## 实现原理
* 通过Android-AccessibilityService模拟用户点击实现
* AccessibilityService监听微信界面的改变，判断界面改变的字符串是否含有'[微信红包]'
* 消息通知：判断Notification.tickerText是否含有'[微信红包]'
* 如果包含'[微信红包]'则执行点击事件
* 在弹出的红包界面上判断是否有'开'这个按钮，如果有则执行点击
* 可能会存在误判，程序是根据字符串判断的红包消息

## 功能介绍
* 1、接收到红包消息，自动打开红包
* 2、群聊天中是否收取自己的红包设置
* 3、发送红包者的过滤可以设置为'【只接收】'或'【不接收】'
* 4、扩展功能-接收红包是软件是否停止工作（通过浮窗可以手动停止或继续）
* 5、扩展功能-接收红包后在红包详情界面停留的时间设置（0~10秒）
* 6、扩展功能-红包标题长度过滤（0~10，0表示不过滤红包标题长度）
* 7、扩展功能-红包标题内容过滤
* 8、扩展功能-延时打开红包
* 9、扩展功能-聊天对话窗保持最新消息

## 最新版本
* 1.0.9

## 联系方式
* QQ 329123330