# 标签/元素
## html标签
html 根
    lang = "en"
    告诉搜索引擎爬虫我们网站什么内容
    竞价排位置 或 SEO


### head标签
head 头
#### 一般在head里的标签
meta
    charset “utf-8”，“gbk”，“gb2313”
    content=""
    name = "keywords"/"description"
    描述

title



### body标签
<body>

####
h1-6
<p>成段展示
<strong>
em斜体
<del>中划线
<address>

div 
span    
<ol type = "1" 或者 “a” “A“ ”i“ ”I“ （排序符号） reversed = "reversed"（顺序逆序） start = "2"(从第几个开始排 只能是数字) >
    <li><li>
</ol>

<ul type = "disc" “square” "circle" 排序符号>
    <li></li>
<ul>
大功能包含功能子项 功能子项功能很相似
e.g.导航栏
 
<img src="" alt = ""如果没有生成图片会出现什么 title = "" 图片提示符鼠标放上去的时候显示的信息 target = "blank"是否打开新网页>
1. 网上url
2. 本地的绝对路径
3. 相对路径
    除非在同一个文件夹里
路径表示 

<a href = "" 链接地址/锚点（id）/ 打电话 “tel:“/ 发邮件“mailto:“ /协议限定符 ”javascript:“></a>

<form method = "get/post“ 发送数据的方式 action = ”“ 发送给谁 >
    username:<input type=“text/password/submit/radio/checkbox(多选)”输入形式 value = 数据值  name=“”数据名 onfocus =得到焦点干什么 if(this.value =='请输入用户名'){this.value='';} onblur = 失去焦点干什么 if(this.value ==''){this.value='请输入用户名';} checked = "checked" 默认选中>
    <select name = "province">
        <option>beijing</optioin>
        <option>shanghai</option>
    </select>
</form>
点submit 发送数据
发送数据
必须有数据名和数据值
radio单选要有统一的name 不一样的value


