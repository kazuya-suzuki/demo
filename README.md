# Modal module  
モーダルのposition指定をdata属性で設定して表示を変化させるものです。  
## ファイル構成
* index.html
* <dl>
    <dt>css</dt>
    <dd>common.css</dd>
    <dd>index.css</dd>
</dl>
* <dl>
    <dt>js</dt>
    <dd>html5shiv.js</dd>
    <dd>jquery-2.0.0.min.js</dd>
</dl>
### 解説
index.htmlを参考にしてもらえればわかりますが  modalを設定したい箇所にaタグを設置しそこに*class="js-modal"*と*data-modal="position設定"*を指定する

###position指定 fixedの場合
<pre>&lt;a href="#" class="js-modal" data-modal="fixed">Aデモ&lt;/a&gt;</pre>

###position指定 absoluteの場合
<pre>&lt;a href="#" class="js-modal" data-modal="absolute">Bデモ&lt;/a&gt;</pre>
