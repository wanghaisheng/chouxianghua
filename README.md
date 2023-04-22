# 大道至简

github也有一些喵言喵语之类的加密玩法，如果把这个拓展到阴阳文化上，会如何


这个和阴阳推演出64卦有什么不同？

![image](https://user-images.githubusercontent.com/2363295/233770525-3cf1ef00-b452-44b2-8523-33c57dc328c2.png)

核心思想是一样的。

         

只是八卦图中长横代表“阳”，用两个短横代表“阴”。

这个和莫尔斯电码中的“嘀嗒”是可以完全匹配的。

         

可以用“阴阳”两个代表所有的字母，其中“阴”代表“点”，“阳”代表“横”。

对照莫尔斯电码表：

A就是点横，即阴阳。

B就是横点点点，即阳阴阴阴。

C就是横点横点，即阳阴阳阴。

D就是横点点，即阳阴阴。

E就是点，即阴。

0就是连续五个点，即连续五个阴。

既然可以表示文字，也可以表示图像啊。

         

所谓图像，无非就是由各种颜色构成。

可以用“阴阳”二元结构给各种颜色进行编码，就可以形成图像了。

视频无非是连续播放的图像，这样视频流也有了。

         

大家现在看的数字电视、手机、电脑，底层就是0和1的二元结构。

         

所以说，“道”可以包罗万象，解释万物，并非是玄学，而是逻辑推理出来的事实。
https://mp.weixin.qq.com/s/ptESxPlr_rqlbwTrkKA3lw


## 中文转换成摩斯电码

https://github.com/hustcc/xmorse

https://github.com/franklinhu/chinese-in-morse-code



## 摩斯电码转换成声音
https://github.com/tangwan/morse

## 摩斯电码转换成阴阳符号

https://github.com/wanghaisheng/yinyangshurufa

## 阴阳符号转换成声音

# chouxianghua

[https://cxh.papapoi.com/](https://cxh.papapoi.com/)

抽象话生成器，一键生成抽象话，附带telegram机器人生成抽象话功能

telegram内，@chouxiangbot即可说抽象话

## 网页版

网页版使用纯js实现功能。

## 搭建telegram机器人功能

接口运行环境为openresty，lua脚本在`lua`文件夹中

更改`run.lua`第一行文件位置为你文件夹的路径

按`run.lua`里的注释，更改相应的key和配置

在`openresty`配置里加上你lua文件的指向配置（需要自己改路径）：

```nginx
#抽象话
location /chouxiang {
    default_type 'text/plain';
    content_by_lua_file /www/wwwroot/qq.papapoi.com/chouxiang/run.lua;
}
```

在将你的机器人webhook接口改为你配置的接口网址

## 词库

欢迎完善
