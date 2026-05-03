------<<--補足説明-->>------

----使用サイトについて----
<<--埋め込み-->>
Twitter : https://publise.twitter.com/
YouTube : 共有→埋め込む
googlemap : 共有→地図を埋め込む
<<--アイコン画像生成-->>
favicon : https://realfavicongenerator.net



----<<--改行について-->>----
通常改行…<br>
モバイル用改行…<br class="br-phone">



----<<--新しいページの追加方法-->>----
どのページも同じつくりになっているため、
適当なhtmlファイル(index.html以外)をコピーして、
<div class="main">の中身を変えることで作ることができる

----メニューバーの追加方法----
右側にあるメニューバーに新しくページを付け足したい場合には、

<tr><td style="font-size:25px;"><a href="htmlの場所">ページ名</a></td></tr>

をコピペ
メニューなどの見出しを付け足したい場合には<td>を<th>にする必要がある



----<<--game.html-->>----
＊2020年ゲームは2021年以降消してよい

左に画像(1280×720推奨)、右に説明文を書く

ゲームの追加方法は

<span class="small">ゲーム名</span>
<div class="game">
	<div><img src="画像" width="100%" height="auto" alt=""></div>
	<div style="text-align: center; width: 100%; border-style:ridge; background-color: white;"><br>
		"説明"
	</div>
</div>
<span class="small">プレイ動画</span><br>
<div class="movie">
	"動画(width="100%" height="100%")"
</div>

をコピペ



----<<--soft.html-->>----
ソフトの追加は

<div class="soft">
	<h3 style="color: lightseagreen">ソフト名</h3>
	<img src="ソフト画像" width="100" height="auto" alt="">
	<a href="ソフトの公式ホームページ" target="_blank"><br><b>ホームページ</b></a><br>
</div>

をコピペ

ソフトは追加すると自動で行が変更されるようになっている



----<<--download.html-->>----
最新版ランチャーは毎年切り替える
ランチャーの追加方法は

<tr><td>2000年版　<a href="ファイル場所"><span class="strong">download</span></a></td></tr>

をコピペ



----<<--タブ、クラスの説明-->>----

----<span>(強調)について----
このホームページではspanのクラスは"large"、"small"、"strong"の3つに分かれており、
large : ページの題名
small : 小見出し
strong : 赤字で強調するだけ
になっている。

----<div class="bg">について----
<div class="small">の横一行全部の背景を設定する

<div class="small"><span class="small">--内容--</span></div>

で使う

----<div class="movie">について----
動画用のクラス

<span class="small">説明</span><br>
<div class="movie">
	"動画(width="100%" height="100%")"
</div>

で使う