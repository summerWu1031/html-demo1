## HTML是谁发明的？
李爵士，他同时发明了HTTP和URL WWW=HTTP+URl

<br>

## HTML先手应该写什么?

```` html
<!DOCTYPE html> 
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
````


* !DOCTYPE html 表示声明文档类型是html



* *html lang="zh-CN" 表示使用的语言是中国的简体中文，一开始的默认是en，表示英语的意思



* meta charset="UTF-8" 表示文件的字符编号为"UTF-8"，适合全人类使用，不建议修改



* Document里面的内容是可以自行更换，是浏览窗口的标题



<br>
<br>


## 常用的表章节的标签有哪些，分别是什么意思?（h1~h6、section、article、main、aside 等等）
<br>
1.h1~h6,表示标题，h1为最大最重要的标题，h2为第二大和第二重要的标题，依此类推。（标题的大小样式可以通过sytle或者css修改）

<br>
<br>


````html
<h1>标题一</h1>
<h2>副标题</h2>
````
<br>

2.section 表示章节

3.article 表示文章

4.p 表示段落

5.header 表示头部

6.footer 表示脚部

7.main 表示主要内容

8.aside 表示旁支内容

~~~~html
  <header>
        <section>第一章</section>
        <p>段落一</p>
        <p>段落二</p>
    </header>
    <main>
        <section>主要章节</section>
        <p>主要段落</p>
        <p>主要段落</p>
    </main>
    <footer>
        <section>结尾章节</section>
        <p>结尾段落</p>
    </footer>
~~~~

## 全局属性有哪些？
* class 类名
* contenteditable 由content内容和editable可编写的组成，表示可被用户编辑
* hidden 隐藏
* id 全局属性定义了一个全文档唯一的标识符(ID)，并不可靠，如果重复使用不会报错，建议尽量少使用
* style 修改样式
* tabindex 用键盘上的Tab键去代替鼠标在页面上选择，tabindex=0 表示最后选择 tabindex=-1 表示不可被选择
* title 包含表示与其所属元素相关信息的文本。 这些信息通常可以作为提示呈现给用户

<br>

## 常用的内容标签有哪些，分别是什么意思（a、strong、em、code、pre 等等）
* a 
````
<a href="www.baidu.com">点击此处访问百度</a>
````

* ol+li ul+li
````
<ol>
        <li>1.是什么</li>
        <li>2.是什么</li>
    </ol>

    <ul>
        <li>无需列表</li>
        <li>没有数字1.2.3排列</li>
    </ul>
````

* dl+dt+dd
````
 <dl>
        <dt>被描述的对象</dt>
        <dd>描述的内容</dd>
    </dl>
````

* pre 和 code 
pre标签包含范围里面的所有空格和换行都会被保留，通常和code搭配使用

````
    <pre>
        <code>
            var a =1;
            console log(a);
        </code>
    </pre>
````

* hr 分割线

* br 换行

* em 强调，重复（主观或者语气上需要强调，样式表现为下划线）

* strong 重要（本身内容很重要，样式表现为加粗）

* q (quote的缩写，引用的意思，为行内元素)

* blockquote 会把q元素变为块级元素


