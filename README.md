##Wechat Emoji
-------------
####作用
在微信开发平台或其他渠道获取到的微信昵称、消息等字符串，若包含emoji符号或转义字符串，自动替换为微信官方提供的emoji表情图片。

####使用方法
1. html页面引入提供的css
2. html加载提供的js
3. 以Jquery为例：
``` javascript
var new_content = $('.nickname').html().emoji();
    $('.nickname').html(new_content);
```
