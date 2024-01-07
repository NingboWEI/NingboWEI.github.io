---
title: I'm not WNB
date: 2024-01-07 00:48:53
categories: 开发日志
pic: /images/1.webp
tags:
- test
toc: true
---
## 测试笔记。
现在是格林威治时间 2024年1月7日，0点51分。
<!--more-->
差不多该睡觉了，但现在小破华为突然开始播放MJ的Beat it， emmmmmmmm，exciting！
![](/images/1.webp)

---
## 顺便测试一些东西
### 代码显示
```c
 int main(void){
    printf("我就是什么都不print你能拿我咋地？\n");
    return 0;
 }
```
简单的C语言hello world示范
### 内容折叠
{% collapse 这是一条折叠内容 open %}

你怎么能打开它
不要啦！快点拉上！！！

{% endcollapse %}

```markdown
    {% collapse 这是一条折叠内容 open %}

    你怎么能打开它
    不要啦！快点拉上！！！

    {% endcollapse %}
```
还不赶快拉上！
### 提示面板
{% colorpanel warning 面板框的标题 %}

公开处刑1号
公开处刑2号

{% endcolorpanel %}
```markdown
   {% colorpanel TYPE 面板框的标题 %}

    公开处刑1号
    公开处刑2号

    {% endcolorpanel %}
```
其中TYPE可以是success/danger/info/warning
### 提示信息
{% alertbox primary "真的有人会看吗" %}
{% alertbox success "应该会有人吧，，，" %}
{% alertbox danger "万一真的没有呢Σ(っ °Д °;)っ" %}
{% alertbox info "不，一定会有人的(・∀・(・∀・(・∀・*)" %}
{% alertbox warning "别看了，说的就是你" %}

```markdown
{% alertbox primary "喵呼呼o(=•ェ•=)m" %}
{% alertbox success "成功啦o(*￣▽￣*)ブ" %}
{% alertbox danger "有危险Σ(っ °Д °;)っ" %}
{% alertbox info "有消息(・∀・(・∀・(・∀・*)" %}
{% alertbox warning "当心哦≧ ﹏ ≦" %}
```

### 模糊字面
我不知道你能不能看得清{% blur 这些东西 %}
```markdown
   我不知道你能不能看得清{% blur 这些东西 %}
```



