Let's Darktable!
写真の扱われ方は昔と大きく変わりました。昔は写真を撮った後、フィルムを現像所にだして、印刷して戻ってくるものでした。しかしデジタル化になって写真は撮った直後からみることが出来るようになりました。しかし家に写真がなくなったのではないでしょうか？写真は携帯やSDカードに入ったままという方もおおいのではないでしょうか？僕も写真はPCには取り込むのですが、大量の写真がフォルダーの中に埋もれてしまい、後から見返すと言うこともなくなってしまい、大切な思い出の写真というものがブログやSNSにしか残らないというような状況です。そこでDarktableの登場です。Darktableを使って撮った写真を自分で管理し、加工し、そして印刷をそて、自分自分で撮った写真の可能性をDarkroomで見つけてみませんか？

# 概要
## Darktableのインストール
Ubuntu Studioには標準でDarktableはインストールされているが、バージョンがふるい。たしか日本語バージョンが含まれていました。今回は現在の安定版の最新3.6を導入するので、古いバージョンのDarktableはアンインストールします。インストールは通常通り  
```bash:インストール
sudo apt install darktable
```

でインストールが行われます。パッケージ等のアップグレードやアップデートは行った上で実行してください。

参考[インストーラー](https://www.darktable.org/install/)  


## さぁDarktableを起動してみましょう
Darktableをインストールしたらやっぱり起動するのがアマチュア道です。LinuxであればTerminalを開いてdarktableと打ち込めば起動する事ができます。通常のアプリケーションですからToolBarやアプリケーションリストにもdarkroomのアイコンを見つけられれば、ダブルクリックで起動する事が出来るはずです。    
<img width="240" alt="architecture" src="images/img001_002.jpg">  


## 画面の構成　(v3.6)
<img width="600" alt="architecture" src="images/img001_003.jpg">  
各所の名前と説明  

|番号|名前|概要|
|:---|:---|:---|
|1|センターエリア<br>Center Area|Lighttabkleでのイメージの一覧やDarkroomでの画像の編集する作業エリア|
|2|左パネル<br>Left Panel|フィルムや写真の情報が表示される|
|3|右パネル<br>Right Panel|画像加工などの機能はこのパネルに集約される|
|4|上のバナー<br>Top Banner|ヒントやメッセージの表示とViewの切替|
|5|上のパネル<br>Top Panel|設定やショートカット|
|6|下のパネル<br>Bottom Panel|ショートカット|
|7|フィルム/タイムラインパネル<br>Film strip/Time line panel|Lighttableの簡易表示|

各パネルは▲▼◀▶で端っこに折りたたむ事ができます。  
参考 [マニュアル v3.6](https://docs.darktable.org/usermanual/3.6/overview/user-interface/screen-layout/)

## Viewの説明
Darktableには6つのViewがあり、これらを切り替えて使います。  これはTop Bannerの右側にあるボタンで選択します。
lighttable, darkroom,そしてotherの中にその他のViewが畳み込まれているので、プルダウンメニューで選択します。
<img width="600" alt="architecture" src="images/img001_002_1.jpg">
  

**Lighttable** これはFilmstripと言われる画像の一覧をみる画面です。Filmstripと言っても実際はフォルダーになります。基本はImportして取り込んだ単位ごとにこのFilmstrapが作られますが、すでに存在する画像が入ったフォルダーをFilmstripとすることもできます。この画面では、画像の取り込み、画像の大まかな選択や分類、削除などができます。ピンぼけしている画像の削除、気に入った画像のレートを上げたり、家族が写っている画像にマークをつけたり、自分の好きなタグをつけたりすることができます。  
<img width="480" alt="lighttable" src="images/img001_004.jpg">  

**Darkroom**  ここが画像加工をするところです。日本語に訳すと暗室となります。フィルム写真の場合、フィルムの画像を感光紙に焼き付ける部屋ですね。まさにここで撮った写真を作り上げていく場所になります。  
<img width="480" alt="darkroom" src="images/img001_005.jpg">  

**Map** これは画像に含まれるGPS情報を読みとって地図上にサムネイルを表示するものです。  
<img width="480" alt="map" src="images/img001_006.jpg">  

**Print**　これは読んで字のごとく印刷です。  
<img width="480" alt="print" src="images/img001_007.jpg">  

**Slidshow**  こちらもスライドショーです。まぁあまり使いませんね。  

**Tethering**  テザリングとはカメラをDarktableから操作するものです。プロのスタジオカメラマンなら欲しい機能ではないでしょうか。libgphoto2のライブラリーを利用してカメラに接続をしてコントロールを行います。僕のCanon 7Dも一応対応しているはずですが、認識できていない状況です。(2021年12月)こちらは後で治せるか調べてみたいものです。直したところで僕には使いみちはなさそうですが。  


## ワークフロー
<img width="480" alt="architecture" src="images/img001_008.jpg">

## Darktableに関係するファイル
<img width="480" alt="architecture" src="images/img001_001.jpg">




# Refence
[Darktabke web page](https://www.darktable.org/)  
[Darktable 3.6 user manual](https://docs.darktable.org/usermanual/3.6/)  
[Darktable Git Hub](https://github.com/darktable-org)  

# PostScript
[My Profile](profile.md)
