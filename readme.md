# 20210313
一、
1. html 为什么叫超文本标记语言:
    + 因为它可以存放图片、文字、语音、视频、等等组成的,超过了文本的范畴.
2. 浏览器内核:
    + 渲染引擎:负责读取网页内容,整理讯息,计算网页的显示方式并显示界面.

二、标签
1. 通常情况下,标签都是成对出现的;
2. 标签分为两种: 包含关系和并列关系;
3. html 基本结构标签(html也叫html文档):
    + body:文档里面的内容写在这里面.
4. 文档类型声明标签:
    + <!DOCTYPE> 文档类型声明,作用就是告诉浏览器使用哪种 Html 版本来显示网页
    ```html
        <!DOCTYPE html> 这句话的作用:当前页面采取的是 html5 版本来显示网页
    ```
   > 注意:
   + <!DOCTYPE> 声明在文档的最顶端(第一行),在 `html`标签的前面;
   + <!DOCTYPE> 不是一个 html 标签,它就是文档类型声明标签。
5. 标签的作用:
   + 如果你想要 body 里的内容具有一定的结构层次感(比如:有大小标题,有段落感,有换行,有空格等等效果你就得使用html
     标签了,这是 html 标签的作用)。
   + 文本格式化标签: 突出文字的重要性，比普通文字重要、显眼:
   > <b> <strong>(推荐使用,语义比b更强烈) <em>等等 