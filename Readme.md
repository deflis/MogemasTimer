モバゲー版アイマス　コスト回復タイマー
======================================

WPFとMVVMとRx(ReactiveExtentions)を用いて、簡単なタイマーアプリを作ります。

要求仕様
--------

モゲマスの仕様としては
+スタミナは3分に一度回復する。
+攻撃コストは1分に一度回復する。
+各コストには最大値が存在する。
+各コストは消費をした瞬間から回復が始まる。
等が挙げられる。

よって、
+タイマーは2つ必要（スタミナ・功コスト）
+回復までの残り時間の目安が欲しい
+回復タイミングを微調整できるとなおよい。
+大体幾つ程度回復したかの目安が欲しい。
というような仕様にしたいと思う。


以下執筆中。。。
ブログにまとめて上げたい。