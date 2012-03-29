#&quot;jQuery.ui.preloadImg&quot; widget

##Description
DOM内の特定の位置にある画像、もしくは特定のパスの画像をプリロードして、コールバックを返すだけのスクリプト。要jQuery UI widget

---
##Required
###jQuery (Developed on 1.7.1)
http://jquery.com/

---
##Demos
http://ranadesign.github.com/jquery-preloadimg

---
##Usage

###Step01
head要素内で jquery.js、jquery.ui.js (要widgetモジュール), jquery.ticker.jsを順番に読み込みます。

	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js"></script>
	<script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.8.18/jquery-ui.min.js"></script>
	<script src="js/jquery.ui.preloadimg.js"></script>

###Step02
comming soon...

###Step03
comming soon...

### Options
オプションの一覧は次の表の通りです。

<table border="1">
<colgroup span="1" class="colh">
<colgroup span="1" class="colh">
<colgroup span="1" class="cold">
<thead>
<tr>
<th>オプション名<br>(option name)</th>
<th>デフォルト値<br>(default value)</th>
<th>型<br>（data type）</th>
<th>備考<br>(note)</th>
</tr>
</thead>
<tbody>

<tr>
<td>srcs</td>
<td>[]</td>
<td>Array</td>
<td>特定の画像をロードしたい時、画像のパスを配列にして渡す。</td>
</tr>
<tr>
<td>interval</td>
<td>100</td>
<td>Number</td>
<td>画像がロードされたかチェックする間隔。単位はミリ秒</td>
</tr>
<tr>
<td>complete</td>
<td>function () {}</td>
<td>Function</td>
<td>渡された画像が全てロード完了した時に実行されるコールバック関数</td>
</tr>
</tbody>
</table>

---
##License
<a href="http://www.opensource.org/licenses/mit-license.html">MIT License</a><br />
参考: <a href="https://secure.wikimedia.org/wikipedia/ja/wiki/MIT_License">MIT License - Wikipedia</a>

---
##Contact
<a href="http://kaelab.ranadesign.com/blog/author/naoki-sekiguchi/">Naoki Sekiguchi - かえラボBlog</a>
