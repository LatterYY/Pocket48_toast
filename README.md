# Pocket48_toast
----
###### 仿口袋直播特效的ASS字幕转换器
---
#### 已知缺陷：
1. 弹幕用户名与内容间存在阴影:
     - ASS字幕机理，有改动方案，但文件大小将成倍增加。暂不处理。
2. 字符显示不全
     - 聚聚们用的字符样式之多，还带表情。一般编码玩不过来，告辞告辞。
3. 原lrc字幕最后5位发言不予转换
     - 一般弹幕最后时间点会超出视频长度。即使转换，也不会显示。
4. 配色丑
     - 审美差，欢迎提供配色方案。
5. 代码写烂
     - 初学者，望斧正。


样例：     
![image](https://github.com/GNZ48live/Pocket48_to_ass/blob/master/Simple.jpg "蕾蕾镇楼")

------------
#### Usage：
```
python PtoA.py ***.lrc (Your file）
```
