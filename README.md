# HTML-10-
HTML响应式Web设计、计算机代码、HTML5 语义
//HTML响应式Web设计
    //什么是响应式Web设计
        //1.RWD指的是响应式Web设计
        //2.RWD能够以可变尺寸传递网页
        //3.RWD对于平板和移动设备是必需的

    //创建响应式设计的一个方法是自己来创建
    <html lang="en-US">
    <head>
    <style>
    .city{
    float:left;
    margin:5px;
    padding:15px;
    width:300px;
    height:300px;
    border:1px solid black;
    }
    </sstyle>
    </head>

    <body>

    <h1>W3School Demo</h1>
    <h2>Resize this responsive pagel!</h2>
    <br>

    <div class="city">
    <h2>London</h2>
    <p>London is...</p>
    <p>It is...</p>
    </div>

    <div class"city">
    <h2>Paris</h2>
    <p>...</p>
    </div>

    <div class="city">
    <h2>Tokyo</h2>
    <p>...</p>
    </div>

    </body>
    </html>


    //使用Bootstrap
        //这是使用现成的CSS框架
        //Bootstrap是最流行的开发响应式web的HTML，CSS，和JS框架
        //Bootstrap帮助开发在任何尺寸都外观出众的站点：显示器、笔记本、平板或手机



//HTML计算机代码元素
    //计算机代码
        var person={
        firstName:"Bill",
        lastName:"Gates",
        age:50,
        eyeColor:"blue"
      }

    //HTML计算机代码格式
    //通常，HTML使用可变的字母尺寸，以及可变的字母间距
    //在显示计算机代码示例时，并不需要如此。
    //<kbd>，<samp>，以及<code>元素都支持固定的字母尺寸和间距

    //HTML键盘格式
    //HTML<kbd>元素定义键盘输入：
    <p>To open a file,select:</p>
    <p><kbd>File|Open...</kbd></p>

    //HTML样本格式
    //HTML<samp>元素定义计算机输出示例：
    <samp>
    demo.example.com login:Apr 12 09:10:17
    Linux 2.6.10-grsec+gg3+e+fhs6b+nfs+gr0501+++p3+c4a+gr2b-reslog-v6.189
    </samp>

    //HTML代码样式
    //HTML<code>元素定义编程代码示例：
    <code>
    var person={firstName:"Bill",lastName:"Gates",age:50,eyeColor:"blue"}
    </code>
    //<code>元素不保留多余的空格和折行：
    <code>
    var person={
      firstName:"Bill",
      lastName:"Gates",
      age:50,
      eyeColor:"blue"
    }
    </code>
    //此行代码输出还是一行
    //如果需要解决这个问题，则必须在<pre>元素中包围代码：
    <code>
    <pre>
    balabala
    </pre>
    </code>

    //HTML变量格式化
    //HTML<var>元素定义数学变量：
    <p>Einstein wrote:</p>
    <p><var>E=m c<sup>2</sup></var></p>

    //标签积累
    //<code>-定义计算机代码文本
    //<kbd>-定义键盘文本
    //<samp>-定义计算机代码示例
    //<var>-定义变量
    //<pre>-定义预格式化文本



//HTML5语义元素
    //语义学可以定义为语言意义的研究
    //语义元素是拥有语义的元素

    //什么是语义元素？
        //语义元素清楚的向浏览器和开发者描述其意义
        //非语义元素的例子：<div>和<span>-无法提供关于其内容的信息
        //语义元素的例子：<form>、<table>以及<img>-清晰的定义其内容

    //HTML5中新的语义元素
    //许多网站包含了指示导航、页眉以及页脚的HTML代码，如：<div id="nav"><div class="header"><div id="footer">
    //HTML提供了定义页面不同部分的新语义元素：
    //<article><aside><details><figcaption><figure><footer><header><main><mark><nav><section><summary><time>

    //HTML5<section>元素
        //<section>元素定义文档中的节
        //根据W3C的HTML文献：“节（section）是有主题的内容组，通常具有标题”。
        //可以将网站首页划分为简介、内容、联系信息等节
        <section>
          <h1>WWF</h1>
          <p>The World Wide Fund Nature(WWF)is...</p>
        </section>

        //HTML5<article>元素
        //<article>元素规定独立的自包含内容。
        //文档有其自身的意义，并且可以独立于网站其他内容进行阅读
        //<article>元素应用场景：
        //1.论坛    2.博客    3.新闻

        //嵌套语义元素
        //在HTML5标准中，<article>元素定义完整的相关元素自包含块
        //<section>元素被定义为相关元素块
        //我们能够使用该定义来解决嵌套元素吗？不
        //在因特网中，您会发现<section>元素包含<article>元素的HTML页面，还有<article>元素包含<section>元素的页面
        //您还会发现<section>元素包含<section>元素，同时<article>元素包含<article>元素

        //HTML5<header>元素
        //<header>元素为文档或节规定的页眉
        //<header>元素应该被用于介绍性内容的容器
        //一个文档中可以有多个<header>元素
        //下例定义页眉
        <article>
          <header>
            <h1>baaa</h1>
            <p>WWF's mission</p>
          </header>
          <p>blaa</p>
        <article>

        //HTML5<footer>元素
        //<footer>元素为文档或节规定页脚
        //<footer>元素应该提供有关其包含元素的信息
        //页脚通常包含文档的作者、版权信息、使用条款链接、联系信息等
        //您可以在一个文档中使用多个<footer>元素
        <footer>
          <p>dhasikfd</p>
          <p>ashfkjs</p>
        </footer>

        //HTML5<nav>元素
        //<nav>元素的定义导航链接集合
        //<nav>元素旨在定义大型的导航链接块。不过，并非文档中所有链接都应该位于<nav>元素中！
        <nav>
        <a href="/html/">HTML</a>|
        <a href="css/">CSS</a>|
        <a href="/js/">JavaScript</a>
        </nav>

        //HTML5<aside>元素
        //<aside>元素的页面主内容之外的某些内容(比如栏目)
        //aside内容应该与周围内容相关
        <p>My family</p>
        
        <aside>
          <h4>Epcot Center</h4>
          <p>blaa</p>
        </aside>

        //HTML5<figure>和<figcaption>元素
        //在书籍和报纸中，与图片搭配的标题很常见
        //标题的作用是为图片添加可见的解释
        //通过HTML5，图片和标题能够被组合在<figure>元素中：
        <figure>
          <img src="pic_mountain.jpg"alt="The Pulpit Rock"width="304"height="228">
          <figcaption>Fig1.-The Pulpit Pock,Norway.</figcaption>
        </figure>

        //为何使用HTML5元素？
        //如果使用HTML4的话，开发者使用他们喜爱的属性名来设置页面元素的样式：
        //如此，浏览器便无法识别正确的页面内容

        //标签积累
        //<article>-定义文章
        //<aside>-定义页面内容以外的内容
        //<details>-定义用户能够查看或隐藏的额外细节
        //<figcaption>-定义<figure>元素的标题
        //<figure>-规定自包含内容，比如图示、图表、照片、代码清单等
        //<footer>-定义文档或节的页脚
        //<header>-规定文档或节的页眉
        //<main>-规定文档的主内容
        //<mark>-定义重要的或强调的文本
        //<nav>-定义导航链接
        //<section>-定义文档的节
        //<summary>-定义<details>元素的可见标题
        //<time>定义日期/时间
        
        

