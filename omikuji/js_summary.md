## おみくじで使ったjsまとめ
* jsで要素を取得する場合はidのほうが扱いやすい
* 配列の要素数：length

### 関数
* this.textContent：文字を表示する
* addEventListener：要素に対してイベントを追加する
	```
		{要素名}.addEventListener('{発生条件}' , function(){
		{こうしてね}
	});
	```
* Math.floor：
* Math.random：0~1の間の整数をランダムにする
* 発生条件の種類
	* click：マウスをクリックした時
	* mousedown：マウスを押している間
	* mouseup：マウスを離した時

* 確率を変える方法
	* 1. Math.randomを使って0~1の間のランダムな数字を発生させて、それを変数に入れる
	* 2. if文の条件文の箇所に1で入れた変数の数字よりも小さい場合は~と記載する
		```
		例
		var n = Math.random();
			if(n < 0.05){
				this.textContent = "大吉"; 5%
			}
		```
