<h1>JavaScript&TypeScript总结</h1>
<h2>JavaScript</h2>
<h3> JavaScript的基本语法</h3>
  <h4>大小写敏感</h4>
     <p>在写JavaScript时，我们需要区分我们变量的大小写，'haha'和'Haha'是不同的两个变量</p>
  <h4>语句</h4>
   <p>语句在结束时可以不加分号</p>
  <h4>变量</h4>
  <ul>
    <li>ECMAScript 的变量是松散类型的，所谓松散类型就是可以用来保存任何类型（如： String、Number、Boolean）的数据</li>
    <li>var变量是局部变量</li>
  </ul>
<h4>标识符</h4>
<ul>
 <li>按照惯例，采用驼峰式命名法</li>
 <li> 标识符的首字母必须是字母，下划线，美元符号</li>
 <li>标识符就是指的变量，函数，属性的名称等</li>
</ul>
<h4>操作符</h4>
<ul>
<li><code>++ --</code>是一元操作符</li>
<li><code>&& || ！</code>是布尔操作符，除下列值为假外其余皆为真： false、null、undefined、''、0、NaN</li>
<li><code>+ - * / %</code>是算数操作符</li>
<li><code><> <= >= == === != !==</code>是关系操作符，<code>===</code>是全等</li>
<li><code>? :</code>是条件（问号）操作符 </li>
</ul>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/6EdRoDqtUnbXjGW" >
<img src="https://s2.loli.net/2022/07/09/6EdRoDqtUnbXjGW.png" alt="图片g了" width="300">
</a>
</div>
</div>
<p>如果条件成立，返回num1；条件不成立返回num2</p>
<h3>语句</h3>
<h4>循环</h4>
<p>if do-while while for for-in for-of break continue switch</p>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/wZapVXs7u2L6vkF" >
<img src="https://s2.loli.net/2022/07/09/wZapVXs7u2L6vkF.png" alt="图片g了" width="300">
</a>
</div>
</div>
<p>与高级语言的循环类似，但不建议采用与高级语言同样格式的循环</p>
<h4>条件语句</h4>
<ul>
<li><code>if </code>语句，<code>if..else</code>语句,<code>switch</code>语句的语法与高级语言的语法类似</li>
</ul>
<h4>函数</h4>
<ul>
<li>函数的格式与高级语言类似function sayHi(name, message) {
    console.log('Hello ' + name + ',' + message);
}</li>
<li>JavaScript的函数和高级语言有区别，主要是JavaScript的数据类型很松散，所以函数的参数类型不需要写，返回值的类型也是，参数个数也可以不对，而不会报错，所以需要仔细检查</li>
<li><strong>注意</strong>：如果你申明了两个一样名字的函数，程序会执行<strong>后写的</strong>函数</li>
</ul>
<h3>数组</h3>
<h4>数组联合</h4>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/JE2ojrtfgep3cqm" >
<img src="https://s2.loli.net/2022/07/09/JE2ojrtfgep3cqm.png" alt="图片g了" width="300">
</a>
</div>
</div>
<h4>堆栈方法</h4>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/sISjTfMbwiqDv1y" >
<img src="https://s2.loli.net/2022/07/09/sISjTfMbwiqDv1y.png" alt="图片g了" width="300">
</a>
</div>
</div>
<h4>队列方法</h4>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/78V1eCcjupWKxTg" >
<img src="https://s2.loli.net/2022/07/09/78V1eCcjupWKxTg.png" alt="图片g了" width="300">
</a>
</div>
</div>
<ul>
<li><code>栈</code>是一种先进后出的数据结构，一切操作都是在栈顶操作，通过实体的特性来选择数据结构</li>
<li><code>队列</code>是一种先进先出的数据结构，适合很多的实体，比如排队</li>
</ul>
<h2>TypeScript</h2>
<h3>TypeScript是什么</h3>
<a href="https://ts.xcatliu.com/" target="_blank">TypeScript官方网站</a>
<p>TypeScript是JavaScript类型的超集（当前我们处于ES5），它可以编译成纯JavaScript。

TypeScript给JavaScript加上可选的类型系统，给JavaScript加上静态类型后，就能将调试从运行期提前到编码期，诸如类型检查、越界检查这样的功能才能真正发挥作用。 TypeScript的开发体验远远超过以往纯JavaScript的开发体验，无需运行程序即可修复潜在bug。</p>
<h3>变量</h3>
<div class="responsive">
<div class="img">
<a target="_blank" href="https://sm.ms/image/I3xF9CR6p8eKUrP" >
<img src="https://s2.loli.net/2022/07/09/I3xF9CR6p8eKUrP.png" alt="图片g了" width="300">
</a>
</div>
</div>
<li><code>let const</code>let和var有相似之处，但是let可以在后面声明类型，也可以不声明可以自动判断一些类型。const声明之后不能改变值</li>
<li>
<h3>解构</h3>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/9dec41333e192d664e6a12fc33df424fa0a4228550b7874bcf7f44a243965b83/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f30382f757669344c48536d434245784168352e706e67"><img src="https://camo.githubusercontent.com/9dec41333e192d664e6a12fc33df424fa0a4228550b7874bcf7f44a243965b83/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f30382f757669344c48536d434245784168352e706e67" alt="image.png" data-canonical-src="https://s2.loli.net/2022/07/08/uvi4LHSmCBExAh5.png" style="max-width: 100%;"></a><br>
<a target="_blank" rel="noopener noreferrer" href="https://camo.githubusercontent.com/c9a53633dc9d414ed314262b07584a81e6cccfbece697d0ccd9d4932f8694b6a/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f30382f354f56447673705574346c41794d472e706e67"><img src="https://camo.githubusercontent.com/c9a53633dc9d414ed314262b07584a81e6cccfbece697d0ccd9d4932f8694b6a/68747470733a2f2f73322e6c6f6c692e6e65742f323032322f30372f30382f354f56447673705574346c41794d472e706e67" alt="image.png" data-canonical-src="https://s2.loli.net/2022/07/08/5OVDvspUt4lAyMG.png" style="max-width: 100%;"></a><br>
</li>
<h3>函数</h3>
<li>在TypeScript中有匿名函数，将函数的返回值设为let，可以自动判断返回类型，console.log(typeof myAdd(1, 2));</li>
<li><code>可选参数</code>可选参数是指，不一定要的参数，可以有，也可以没有，可选参数必须写在必须参数后面，function greeting(firstName: string, lastName?: string)</li>
<h3>类</h3>
<p>类是属性（有些什么）和函数（能干什么）的集合，是生成对象（Object）或类实例的模板。(和高级语言一样）</p>
<h4>类的定义</h4>
<a href="https://sm.ms/image/Fm4BzpiJl1DMgWN" target="_blank"><img src="https://s2.loli.net/2022/07/09/Fm4BzpiJl1DMgWN.png" alt="g" width="300"></a>
<p>这里的类和高级语言的类相似，只是语法不同，其核心是一个东西</p>

