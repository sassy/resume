
* 渡辺 悟史(わたなべさとし)
* 最終学歴:芝浦工業大学　システム工学部　電子情報システム学科　卒業

# スキル

* C言語
 * 組込みアプリケーション開発
* Java
 * Androidアプリケーション開発
 * JSP/サーブレット
* FrontEnd(HTML/SVG/CSS/DOM/JavaScript)開発
 * jQuery
 * Backbone.js
 * React.js
 * Angular (v2-)
* cordovaによるAndroid/iOSアプリケーション開発
* Electronによるデスクトップアプリ開発
* PHPによるWebアプリケーション開発
 * Ethna
* Node.jsを使ったサーバーやツール開発
 * express
 * koa.js
* Python


# 経歴

## 株式会社ACCESS 2005年4月-2011年8月

### NetFront Browser v3のコアエンジン開発
* 2005年5月-2008年3月
* 組込みむけブラウザである、NetFront Browserのレンダリングエンジンの開発とメンテナンスを行う。
* 入社時から2007年1月までは、主にSVGモジュールのオーナーとして、新規機能の開発(W3CのSVGTiny1.2対応やJavaでSVGを利用するための仕様であるJSR-226対応)や品質向上(不具合修正やアンチエイリアシング対応)を行う。
* 2007年2月以降は案件の窓口とブラウザレンダリングエンジンとメモリマネージャの不具合修正、品質向上の活動を行う。

### キャリアサービス試作案件
* 2005年8月 - 2005年12月
* キャリア提案の新規サービス(SVGを利用したメール・HTMLを利用した待ち受け)の試作のための標準版の開発
* キャリアとの仕様の調整と標準版のカスタマイズ

### 組込み向けブラウザ次期バージョンの開発
* 2008年4月 -2010年5月
* 組込み向けにHTML5に対応させたブラウザの開発
* HTML/DOM/画像処理を担当する5人ぐらいのチームリーダーとして、サポートする仕様の調整やチーム間のコミュニケーション、チームメンバーの技術的サポートを行う。
* 自らは画像表示やDOMメソッドの設計とコーディングを行う。

組込み向けにHTML5に対応させたブラウザの開発を一から行いました。
HTML/DOM/画像処理を担当する5人ぐらいのチームリーダーとして、サポートする仕様の調整やチーム間のコミュニケーション、チームメンバーの技術的サポートを行いました。
また、自らは画像表示やDOMメソッドの設計とコーディングを行いました。
C言語でメモリを気にしてコーディングする経験は今も生きています。


### Android用ブラウザ NetFront Life Browserの開発
* 2010年6月 -2011年3月
* Android用ブラウザアプリケーションでの、NetFront Life Browserの開発
* 今まで行ってきたBtoBではなく、初めてのBtoCプロジェクトで、Androidマーケットで直接ユーザにダウンロードしてもらうアプリケーションを開発
* ページローディング中のサムネイル表示、ダウンローダー、急上昇ワードの設計・実装
 * ページローディング中のサムネイル表示は特許出願を行った。
* 法人向けブラウザとして、マーケットにリリースしたものをベースにカスタマイズする案件での、案件チームとの窓口も行う。
* 社内で初めてアジャイル開発(スクラム)を導入

Android用ブラウザアプリケーションでの、NetFront Life Browserの開発を行いました。
社内では、今まで行ってきたBtoBではなく、初めてのBtoCプロジェクトで、Androidマーケットで直接ユーザにダウンロードしてもらうアプリケーションを開発することができました。
また、社内での初めてのスクラムでの開発でした。

設計実装は、ページローディング中のサムネイル表示、ダウンローダー、急上昇ワードの設計・実装を行いました。ページローディング中のサムネイル表示は特許出願を行い、特許を取得しました。
サムネイル表示はWebViewをサムネイルとして右下に表示させることと、全体は画像に差し替えるという実装になり、ちらつかないように試行錯誤して実装しました。

法人向けブラウザとして、マーケットにリリースしたものをベースにカスタマイズする案件での、案件チームとの窓口も行いました。


### 広告配信システムのクライアント側開発
* 2011年4月 -2011年8月
* Androidアプリケーションへの広告配信のしくみを検討し、Androidクライアント側のSDKの開発

## グリー株式会社(2011年9月-2013年2月)
### Android版SNSアプリケーション「GREE」の開発
* 2011年9月 -2011年12月
* SNS「GREE」を行うためのアプリケーションのAndroid版の開発

#### Global向けAndroid版SDK及びGlobal版Android版SNSアプリケーション「GREE」の開発
* 2011年12月  - 2013年２月
* Global版GREE Android SDKで作成されたゲームでSNS「GREE」を行うためのダッシュボードビューの開発
* SDKを使って「GREE」アプリの開発

グリーSNSのAndroidを国際化対応したアプリにリニューアルすべく、一からアプリ開発とそれに必要なSDKの開発を行いました。
WebViewベースのハイブリットアプリでしたが、スライドメニューやPull To Refreshといった部分はネイティブで自前の実装を行いました。
フロント部分のサーバーはnode.jsでそこからフロント画面を取得する形式でした。
スライドメニューは当時はそのようなWidgetがなかったので、自前の実装でしたが、Viewを重ねる部分の実装に苦労しました。
Pull to Refreshも自前実装だったため、引っ張る部分にViewを入れてタッチが外れたら元に戻す等の実装をいくつか試作し、一番パフォーマンスが上がる実装を選択しました。
当初はWebViewを重ねてキャッシュしておくことで画面がすぐにバックできる仕様でしたが、
WebViewを重ねると重くなることがわかり、WebView一枚にするという決断をしました。
社内でも評価されたプロジェクトでした。

## zigsow株式会社 2013年３月
* キャンペーンサイトのフロントエンド開発

## フリーランス 2013年7月-2013年10月
* 株式会社CONNEXTにて NetFront NX DTVの開発の業務委託

## 株式会社ACCESS 2013年11月-2016年11月

### NetFront Broser NXの開発
* 2013/11-2014/04
* セットトップボックス向け Android移植 (ndk/NativeActivity  DTVProfile(キーイベント対応版))

### メーカー向けHTML5を利用したアプリSDK開発
* 2014/05-2016/07
* cordovaをベースにマルチプラットフォームでアプリを作るためのSDKを開発
* C言語やJava/Objective-Cで機器との通信やSVGのレンダリング等を行う
* 上記をcordovaのプラグインとして提供する

cordovaをベースにマルチプラットフォームでアプリを作るためのSDKを開発を行いました。
C言語やJava/Objective-Cで機器との通信やSVGのレンダリング等を行う開発を行い、
これをcordovaのプラグインとして提供するという構成でした。

当初はお客様の要求はHTML5でのクロスプラットフォームだったので、
cordovaを提案し、社内アプリでのSDKとして提供できるような構成にしました。

###  Vehicle API  polyfill
* 2014/10-2014/11
* Vehicle APIを使ったHTMLアプリを動かすためのJavaScrpit polyfillを作成
 * https://rawgit.com/w3c/automotive-bg/master/snapshots/vehicle_spec_snapshot_latest.html
  * https://rawgit.com/w3c/automotive-bg/master/snapshots/data_spec_snapshot_latest.html
* 車載のデータを取得し、APIで取得できるようにする


### 車載SNS連携試作
* 2014/5
* Windows Azure上で SNSを取得してAPIで提供 C#
* 車載器のクライアントからAzure上のWebAPIを叩いて情報を取得
* Client側はJava

### ACCESS Connect車載Profile
* 2015/06-2015/08
* クライアント側で ヒートマップを leaflet.js + heatmap.js　で作る
* React.jsでフロントエンド部分を開発する

### 簡易node.jsアプリケーションダッシュボード + node.jsアドオン開発試作
* 2016/08
* node.jsのWebアプリケーションを起動・終了及び起動状況確認を行なう簡易Webアプリケーション(node.jsで開発)
* node.jsでC/C++で実装させた機能を呼び出すアドオンの開発
 * アドオン開発のために調査したものは => http://qiita.com/sassy_watson/items/25241868be12a425f86a

### ネットワーク管理システムのフロントエンド開発
* 2016/09-2016/11
* ネットワークの状況を確認するためのシステム
* Web APIを叩いて状況を表示させるためのフロントエンド(HTML/CSS/JavaScript) + フロントエンドサーバー開発 (Java Servelet)

## 株式会社カケハシ (2016年12月-)

### 電子薬歴システムMusibiの開発
* 2016/12-
* クライアントサイドはAngular + サーバーサイド(APIサーバー)はPython

## 資格

* 平成15年7月 CG検定2級
* 平成15年7月 画像処理検定2級
* 平成23年5月 基本情報技術者試験

## 特許

* 特開2012-078925 "情報表示装置および情報表示プログラム"
 * リンク先のウェブページの取得に時間がかかる場合でも、元のウェブページの閲覧を継続できるようにする。


## その他
* 2012年1月 @ITで「Androidアプリ開発テスト入門 第3回 Androidアプリを“超”魅力的にする3種類のUIテスト」の記事執筆
  http://www.atmarkit.co.jp/fsmart/articles/androidtest03/01.html

### 開発したnode.jsのモジュール
* https://www.npmjs.com/~sassy

### 開発したLINEClovaスキル
* https://clova.line.me/clova-ai/skillstore/skill/io.github.com.sassy.nogibirthday
* https://clova.line.me/clova-ai/skillstore/skill/io.sassy.github.syukkinsupport
* https://clova.line.me/clova-ai/skillstore/skill/com.github.sassy.kawaii
* https://clova.line.me/clova-ai/skillstore/skill/com.github.sassy.kanpai
* https://clova.line.me/clova-ai/skillstore/skill/com.github.sassy.newterm
