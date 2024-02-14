## emmet 사용법

div.classname <p>
~~~css
<div class="classname"></div>
~~~
div#idname <p>
~~~css
<div id="idname"></div>
~~~
div>ul>li<p>
~~~css
<div>
    <ul>
        <li>
        </li>
    </ul>
</div>
~~~
div>ul+ol<p>
~~~css
<div>
    <ul></ul>
    <ol></ol>
</div>
~~~

div>ul*5<p>
~~~css
<div>
    <ul></ul>
    <ul></ul>
    <ul></ul>
    <ul></ul>
    <ul></ul>
</div>
~~~
div>ul>li^ol<p>
~~~css
<div>
    <ul>
        <li>
        </li>
    </ul>
    <ol>
    </ol>
</div>
~~~
div>(header>ul>li*2>a)+footer>p
~~~css
<div>
    <header>
        <ul>
            <li><a href=""></a></li>
            <li><a href=""></a></li>
        </ul>
    </header>
    <footer>
        <p></p>
    </footer>
</div>
~~~
p{hello}
~~~css
<p>hello</p>
~~~
enum으로 차례대로 자동 숫자 할당하기
p.class${item $}*5
~~~css
<p class="class1">item 1</p>
<p class="class2">item 2</p>
<p class="class3">item 3</p>
<p class="class4">item 4</p>
<p class="class5">item 5</p>
~~~