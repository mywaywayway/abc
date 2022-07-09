<title>HTML&CSS总结</title>
<h1>HTML</h1>
<h2>这是一个最基础的HTML</h2>
<body>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/iN2UlMnOwkPEeZm">
          <img src="https://s2.loli.net/2022/07/08/iN2UlMnOwkPEeZm.png" alt="图片文本描述" width="300" height="200">
        </a>
    </div>
</div>
<ol type="1">
<li><code>&lt;!DOCTYPE html&gt;</code>: 声明文档类型。出于历史原因需要，现在可有可无。</li>
<li><code>&lt;html&gt;&lt;/html&gt;</code>: <code>&lt;html&gt;</code>元素。这个元素包裹了整个完整的页面，是一个根元素，<strong>其它元素都嵌套到其中</strong>。</li>
<li><code>&lt;head&gt;&lt;/head&gt;</code>: <code>&lt;head&gt;</code>元素。 这个元素是一个容器，它包含了所有你想包含在HTML页面中但不想在HTML页面中显示的内容。这些内容包括你想在搜索结果中出现的关键字和页面描述，CSS样式，字符集声明等等。</li>
<li><code>&lt;title&gt;&lt;/title&gt;</code>: 设置页面标题，出现在浏览器标签上，当你标记/收藏页面时它可用来描述页面。</li>
<li><code>&lt;body&gt;&lt;/body&gt;</code>: <code>&lt;body&gt;</code>元素。 包含你能在页面看到的所有内容，包括文本，图片，音频，游戏等等。</li>
</ol>
<h2>常用元素</h2>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/nMKWk2yjsBoJGEh" >
          <img src="https://s2.loli.net/2022/07/08/nMKWk2yjsBoJGEh.png" alt="图片文本描述" width="300" height="200">
        </a>
    </div>
</div>
<h2>超链接</h2>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/SZCxF4ghIs1PWcN" >
          <img src="https://s2.loli.net/2022/07/08/SZCxF4ghIs1PWcN.png" alt="图片文本描述" width="3000" height="20">
        </a>
    </div>
</div>
<ol type="1">
<li><code>&lt;herf&gt;</code>就是将要转跳的页面的url</li>
<li><code>&lt;target&gt;</code><code>&lt;_blank</code>就是用新的页面打开默认为原网页打开</li>
<p>百度一下为超链接的显示</p>
</ol>
<h2>图片及文件路径 img</h2>
<ol type="1">
<h2> <code>&lt;img src="https://mdbootstrap.com/img/logo/mdb192x192.jpg" alt="MDB Logo" width="200" height="200"> </code></h2>
     <li> <code>src</code>: 图片的url</li>
       <li><code>::mark alt</code>: 请求失败返回的字符串</li>
     
</ol>
<h1>表格</h1>
<p>表格的创建</p>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/LVoRyjQgD4hFqrY" >
          <img src="https://s2.loli.net/2022/07/08/LVoRyjQgD4hFqrY.png" alt="图片g了">
        </a>
    </div>
<p>代码中<code>&lt;tr&gt</code>表示行，<code>&lt;th&gt</code>表示每一列的属性名称如id，<code>&lt;td&gt</code>表示数据</p>
</div>

<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/WeGvDtLXy13ZRBV" >
          <img src="https://s2.loli.net/2022/07/08/WeGvDtLXy13ZRBV.png" alt="图片g了">
        </a>
    </div>
</div>
<h2>列表</h2>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/74kJl5wPQMdtZyg" >
          <img src="https://s2.loli.net/2022/07/08/74kJl5wPQMdtZyg.png" alt="图片g了">
        </a>
    </div>
</div>
<p> 运行结果如下</p>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/dnpwIcZbhDxGyTf" >
          <img src="https://s2.loli.net/2022/07/08/dnpwIcZbhDxGyTf.png" alt="图片g了">
        </a>
    </div>
</div>
<li>
<p dir="auto"><code>&lt;div&gt;&lt;/div&gt;,&lt;span&gt;&lt;/span&gt;</code>: <code>&lt;div&gt;</code>元素是块级元素，它可用于组合其他 HTML 元素的容器，没有其他意义。 <code>&lt;span&gt;</code>元素是内联元素，可用作文本的容器<code>&lt;span&gt;</code>元素也没有特定的含义。</p>
</li>
<h2>表单</h2>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/MeXWVs9qk3ZDAEc" >
          <img src="https://s2.loli.net/2022/07/08/MeXWVs9qk3ZDAEc.png" alt="图片g了">
        </a>
    </div>
</div>

<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/iq8ZdxHLC6jXF3E" >
          <img src="https://s2.loli.net/2022/07/08/iq8ZdxHLC6jXF3E.png" alt="图片g了" >
        </a>
    </div>
</div>
<h1>css</h1>
<h2>什么是css</h2>
<p>CSS是级联样式表（Cascading Style Sheets）的缩写。HTML 用于撰写页面的内容，而 CSS 将决定这些内容该如何在屏幕上呈现。</p>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/yr9ukeKPmqD5fBW" >
          <img src="https://s2.loli.net/2022/07/08/yr9ukeKPmqD5fBW.png" alt="图片g了">
        </a>
    </div>
</div>
<p>p{}是所有的<code>&lt;p&gt </code>都是这个格式</p>
<p>如果你将一个<code>&lt;p&gt </code>的id设为fff，而且只想要id为fff的变换格式可以上面的方法</p>

<p><code>&lt;p&gt </code>的定义格式</p>
<h2>css的引入</h2>
<a href="https://sm.ms/image/tvDS756MP9mQG3F" target="_blank"><img src="https://s2.loli.net/2022/07/08/tvDS756MP9mQG3F.png" alt="QQ图片20220708234112.png"></a>
<li><code>&lt;link rel="stylesheet" type="text/css" href="mystyle.css"&gt;</code>:<code>href</code>表示要引入的样式路径。</li>
<li><code>&lt;style&gt;&lt;/style&gt;</code>:在这里写内部样式。</li>
<h2>css的颜色</h2>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/yr9ukeKPmqD5fBW" >
          <img src="https://s2.loli.net/2022/07/08/yr9ukeKPmqD5fBW.png" alt="图片g了" width="300">
        </a>
    </div>
</div>
<h2>css的尺寸</h2>
<a href="https://sm.ms/image/s9TxUqDyHgjeFtZ" target="_blank"><img src="https://s2.loli.net/2022/07/08/s9TxUqDyHgjeFtZ.png" alt="QQ图片20220708235737.png"></a>
<p>example-1的width占屏幕的100%，宽度200px(单位)</p>
<p>example-2的width占100px(单位），宽度500px(单位)</p>
<p><strong>一钟是相对大小，一种的绝对大小，应该经量使用相对大小</strong></p>
<h2>对齐</h2>
<p><strong>对齐</strong>,我们可以简单的设置text-align属性为left, center, right即可（显然缺省的是左对齐），上例中已有相关的应用。</p>
<h2>盒子模型</h2>
<P>模型如下</P>
<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/H8DpXO94VS5egqP" >
          <img src="https://s2.loli.net/2022/07/09/H8DpXO94VS5egqP.png" alt="图片g了" width="300">
        </a>
    </div>
</div>
<ul>
<li> Content 盒子的内容，如图片文本</li>
<li> Padding 填充爷教内边距</li>
<li> Border 边框，默认不显示</li>
<li> Margin 外边距，边框以外与其它元素的区域</li>
</ul>

<h2>边框与边距</h2>
<li>
<p dir="auto">CSS边框和边距</p>
<ul dir="auto">
<li><code>border-style</code>:用于设置元素所有边框的样式，或者单独地为各边设置边框样式。</li>
<li><code>border-width</code>:用于为元素的所有边框设置宽度，或者单独地为各边边框设置宽度。</li>
<li><code>border-color</code>:设置元素的所有边框中可见部分的颜色，或为 4 个边分别设置颜色。</li>
<li><code>margin</code>:外边距
<ul dir="auto">
<li><code>margin-bottom</code>:设置元素的下外边距。</li>
<li><code>margin-left</code>:设置元素的左外边距。</li>
<li><code>margin-right</code>:设置元素的右外边距。</li>
<li><code>margin-top</code>:设置元素的上外边距。</li>
</ul>
</li>
<li><code>padding</code>:内边距
同外边距属性。</li>
</ul>
</li>
<h1>组合选择器</h1>
<h2>后代组合器</h2>  

<div class="responsive">
      <div class="img">
        <a target="_blank" href="https://sm.ms/image/GQUuOE2cI5SB1xF" >
          <img src="https://s2.loli.net/2022/07/09/GQUuOE2cI5SB1xF.png" alt="图片g了" width="300">
        </a>
    </div>
</div>
<p>在HTML文件中 div class="haha"内里面背景颜色会变成黄色，其他的则不影响</p>
<h2>后代组合器</h2>

<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/SyWig9jrEXkBKPJ" >
<img src="https://s2.loli.net/2022/07/09/SyWig9jrEXkBKPJ.png" alt="图片g了" width="300">
</a>
</div>
</div>
<p>在haha类中如果直接是它的子类则会受影响，如果不是它的直接子类比如嵌套了span，则不受影响</p>

</body>

