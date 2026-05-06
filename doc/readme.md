# BitDeck10

<a href="image/BitDeck10_01.jpg"><img width=400 height=300 src="image/BitDeck10_01.jpg"></a>

マクロ用のキー10個、プッシュボタン付きのロータリーエンコーダ1個、状態表示用の白黒OLEDを備えています。

## はじめに

本製品は電子工作キット（組み立て式）です。完成品ではありません。以下の内容をご理解・ご了承のうえご使用ください。

### 1. 組み立てに関する責任

本製品は購入者ご自身による組み立て（半田付け作業を含む）が必要です。
組み立て不良、配線ミス、部品の取り付け間違い等に起因する動作不良・故障について、当方は一切の責任を負いません。

---

### 2. 作業時の安全について

組み立てには半田ごて等の工具を使用します。作業中の火傷、けが、事故等について、当方は責任を負いません。
十分に安全に配慮し、適切な環境で作業を行ってください。

---

### 3. 電気的トラブル・機器への影響

本製品の使用により、接続したPCや周辺機器に不具合・損傷が生じた場合でも、当方は責任を負いません。
特にショートや誤配線による損傷には十分ご注意ください。

---

### 4. 互換性・動作保証について

本製品はすべてのOS、ソフトウェア、機器との互換性および完全な動作を保証するものではありません。
使用環境により動作が異なる場合があります。

---

### 5. 部品の個体差・外観について

3Dプリント部品には積層痕や微細な歪みなど、製造上の個体差があります。これらは仕様であり、不良品ではありません。
また、部品の色味や質感が写真と異なる場合があります。

---

### 6. 改造・カスタマイズについて

本製品の改造、ファームウェア変更、部品交換等は購入者の責任で行ってください。
これらに起因する不具合や損害について、当方は責任を負いません。

---

### 7. サポート範囲について

基本的な組み立てに関する情報は提供しますが、すべての環境や応用的な使用方法についてのサポートは保証していません。
また、個別のトラブル解決をお約束するものではありません。

---

### 8. 免責の範囲

本製品の使用または使用不能から生じたいかなる損害（直接的・間接的損害を含む）についても、当方は一切の責任を負いません。


## 組立準備

### 内容物の確認

本製品には下記が含まれております。
万が一、不足や破損がある場合はお買い上げ１か月以内にBoothのフォームよりご連絡ください。

<table>
  <thead>
    <tr>
      <th style="text-align:left;">部品名</th>
      <th style="text-align:right;">数量</th>
      <th style="text-align:center;">写真</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>BitDeck10 基板</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/pcb-front.jpg">
          <img width=80 height=60 src="image/pcb-front.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>BitDeck10 ボトムケース</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/bottomcase.jpg">
          <img width=80 height=60 src="image/bottomcase.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>BitDeck10 アッパーケース</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/uppercase.jpg">
          <img width=80 height=60 src="image/uppercase.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>Seeed Studio XIAO RP2040</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/xiao-rp2040.jpg">
          <img width=80 height=60 src="image/xiao-rp2040.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>OLEDモジュール</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/oled.jpg">
          <img width=80 height=60 src="image/oled.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>小信号用ダイオード 1SS178</td>
      <td style="text-align:right;">11</td>
      <td style="text-align:center;">
        <a href="image/diodes.jpg">
          <img width=80 height=60 src="image/diodes.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>Kailh キーソケット</td>
      <td style="text-align:right;">10</td>
      <td style="text-align:center;">
        <a href="image/socket.jpg">
          <img width=80 height=60 src="image/socket.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>Outemu Linear Red キースイッチ</td>
      <td style="text-align:right;">10</td>
      <td style="text-align:center;">
        <a href="image/keyswitch.jpg">
          <img width=80 height=60 src="image/keyswitch.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>キーキャップ DSA PBT 白</td>
      <td style="text-align:right;">10</td>
      <td rowspan="3" style="text-align:center;">
        <a href="image/keycaps.jpg">
          <img width=80 height=60 src="image/keycaps.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>キーキャップ DSA PBT 赤</td>
      <td style="text-align:right;">1</td>
    </tr>
    <tr>
      <td>キーキャップ DSA PBT 橙</td>
      <td style="text-align:right;">1</td>
    </tr>
    <tr>
      <td>ロータリーエンコーダ ALPS EC10E1220503</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/encoder.jpg">
          <img width=80 height=60 src="image/encoder.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>タクトスイッチ 北陸電気工業 KSMC613A</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/tactswitch.jpg">
          <img width=80 height=60 src="image/tactswitch.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ロータリーエンコーダ THQWGD001Cパーツ
        <ul>
          <li>ホイール
          <li>軸
          <li>軸押さえ
          <li>左カバー
          <li>右カバー
        </ul>
      </td>
      <td style="text-align:right;">1セット</td>
      <td style="text-align:center;">
        <a href="image/THQVWGD001C.jpg">
          <img width=80 height=60 src="image/THQVWGD001C.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ピンヘッダー 1x4<br/>
        OLED同梱のものと別の金色の足の方を使用
      </td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/4pin-header.jpg">
          <img width=80 height=60 src="image/4pin-header.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ピンヘッダー 1x7<br/>
        <strong>※位置合わせ用：半田付けしません</strong><br/>
        XIAO RP2040付属の場合は2個、XAIOのケースに同梱されています
      </td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/7pin-header.jpg">
          <img width=80 height=60 src="image/7pin-header.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>プラスネジ M2-0.4 5mm</td>
      <td style="text-align:right;">2</td>
      <td rowspan="2" style="text-align:center;">
        <a href="image/screw.jpg">
          <img width=80 height=60 src="image/screw.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ナット M2-0.4</td>
      <td style="text-align:right;">2</td>
    </tr>
    <tr>
      <td>キャップボルト M2-0.4 10mm</td>
      <td style="text-align:right;">4</td>
      <td style="text-align:center;">
        <a href="image/capbolt.jpg">
          <img width=80 height=60 src="image/capbolt.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ゴムシート 約3x10x2mm</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/rubber.jpg">
          <img width=80 height=60 src="image/rubber.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>ゴム足</td>
      <td style="text-align:right;">4</td>
      <td style="text-align:center;">
        <a href="image/rubber_feet.jpg">
          <img width=80 height=60 src="image/rubber_feet.jpg">
        </a>
      </td>
    </tr>
    <tr>
      <td>六角レンチ 1.5mm</td>
      <td style="text-align:right;">1</td>
      <td style="text-align:center;">
        <a href="image/allenkey.jpg">
          <img width=80 height=60 src="image/allenkey.jpg">
        </a>
      </td>
    </tr>
  </tbody>
</table>

※キーキャップは10個使用しますが、レイヤーキー等の色分け用に赤・橙１個ずつ余分に入れております。

---

### 組立に必要な工具類

組立には下記の工具等が必要となりますのでご用意ください。
* はんだごて 15～20W程度のもの（セラミックヒーターが望ましい）
* こて台
* こて先クリーナー
* はんだ（電子工作用）
* ニッパー
  * 半田付け後の部品の足を切るのに使用
* プラスドライバー 0番
* USB-Cケーブル
  * PCとの接続用。データ通信対応のもの。PC側はTYPE-Aでも可。
* PC
  * ファームウェアの書き込み、動作確認用
* つまようじ 2本 
    * 組立後のRESET/BOOTボタン押下用

#### あると便利なもの

* 作業用の耐熱マット
* マスキングテープ
  * 半田付け時の部品の固定用
* フラックス
  * 半田付けをする個所に事前に塗布すると半田付けしやすくなります。
* フラックスリムーバーもしくはイソプロピルアルコール
  * 塗布したフラックスの除去用
* はんだ吸い取り線・はんだ吸い取り器
* ピンセット
* ラジオペンチ
* テスター
  * 導通の確認用
* ルーペ
  * 半田付けの確認用
* キーキャップ・キー引き抜き工具

---

## 組立手順

基板の表面・裏面両方に部品を半田付けしていきます。部品を取り付ける面や方向に気を付けてください。

基本的には背の低い部品から付けていきます。

あまり神経質になりすぎる必要はないですが、XIAO RP2040やOLEDモジュールなどは熱や静電気に弱いので、加熱しすぎ等にご注意ください。

---

### 基板裏面への部品の取り付け

<a href="image/pcb-back.jpg"><img width=600 height=400 src="image/pcb-back.jpg"></a>

---

#### ダイオード

ダイオードには極性があるので、向きを間違えずに実装してください。
部品のライン（緑帯）を、基板のシルク印刷のダイオード記号の縦線（バー）と合わせて差し込んでください。

<a href="image/d_soldering01.jpg"><img width=300 height=200 src="image/d_soldering01.jpg"></a>

本製品の基板上ではダイオードはすべて同じ向きになります。

ダイオード両端の足を曲げ、基板に差し込みます。
基板を返す際に抜け落ちないようにマスキングテープ等で固定するか、写真のように足を少し開いて動かないようにします。

<a href="image/r_soldering02.jpg"><img width=300 height=200 src="image/r_soldering02.jpg"></a>

まず片足を半田付けし、部品にずれが無いかを確認してからもう片方の足を半田付けし、余分な足はニッパーでカットしてください。

<a href="image/d_soldering02.jpg"><img width=300 height=200 src="image/d_soldering02.jpg"></a>

---

#### キーソケット

向きに気を付けて裏面の白い印刷の形状に合わせてソケットをはめ込み、そのまま裏面から端子を半田付けします。

<a href="image/socket_soldering01.jpg"><img width=300 height=200 src="image/socket_soldering01.jpg"></a>

この時、ソケットが浮かないように、マスキングテープで固定するか、軽く上から押さえながら半田付けします。（手で押さえる場合はやけどに注意してください）

足の形が複雑なので少々半田付けが難しいですが、端子の先の□の部分をこて先で加熱し、端子の脇に半田を流し込むようにすると付けやすいです。

<a href="image/socket_soldering03.jpg"><img width=300 height=200 src="image/socket_soldering03.jpg"></a>

---

#### XIAO RP2040

基板にはピンヘッダ用の穴が開いていますが、高さを抑えるためにピンヘッダやコンスルーは使用せずに基板にXIAO RP2040を直接半田付けします。
同梱の7ピンヘッダを使用して位置合わせをします。
<strong>ピンヘッダは半田付けしないでください。</strong>

ピンヘッダを下記写真のように基板の表側から差し込みます。

<a href="image/2040_soldering01.jpg"><img width=300 height=200 src="image/2040_soldering01.jpg"></a>

XIAO RP2040をUSBコネクタを外側にして差し込みます。

<a href="image/2040_soldering02.jpg"><img width=300 height=200 src="image/2040_soldering02.jpg"></a>

各ピンの位置を合わせてから、まずは1つのピンのみを半田付けします。

<a href="image/2040_soldering03.jpg"><img width=300 height=200 src="image/2040_soldering03.jpg"></a>

ピンヘッダを抜き、ずれが無いことを確認してから最初に半田付けしたピンから対角側のピンを半田付けします。

<a href="image/2040_soldering04.jpg"><img width=300 height=200 src="image/2040_soldering04.jpg"></a>

最終的にずれが無いことを確認し、残りのすべてのピンを半田付けします。

<a href="image/2040_soldering05.jpg"><img width=300 height=200 
src="image/2040_soldering05.jpg"></a>

---

※基板上にI2Cプルアップ抵抗のためのパターン(R1, R2)がありますが、OLEDモジュール上にプルアップ抵抗が入っているため、部品の取り付けは不要です。
(写真には抵抗が取り付けられた状態で写っています)

---

### 基板表面への部品の取り付け

<a href="image/pcb-front.jpg"><img width=600 height=400 src="image/pcb-front.jpg"></a>

---

#### OLED

OLEDはピンヘッダを介して基板に取り付けます。

※ピンヘッダはOLED付属のものではなく、OLEDと別に梱包してある金色の足のものを使用してください。
OLED付属のピンヘッダで取り付けてしまい、ケースと干渉した場合は、ピンヘッダの干渉している箇所をニッパーでカットしてください。

まずはOLEDの裏面からピンヘッダの短い方の足を差し込みます。

<a href="image/oled_soldering01.jpg"><img width=300 height=200 src="image/oled_soldering01.jpg"></a>

反対側から半田付けしますが、足が上面に完全には出ないので、スルーホール(基板の穴)に半田を流し込むような感じで取り付けます。

<a href="image/oled_soldering02.jpg"><img width=300 height=200 src="image/oled_soldering02.jpg"></a>

端の1ピンを取り付けたら、取り付けたピンを加熱しながらピンの角度が垂直になるように調整します。（火傷に注意してください）

<a href="image/oled_soldering03.jpg"><img width=300 height=200 src="image/oled_soldering03.jpg"></a>
<a href="image/oled_soldering04.jpg"><img width=300 height=200 src="image/oled_soldering04.jpg"></a>
<a href="image/oled_soldering05.jpg"><img width=300 height=200 src="image/oled_soldering05.jpg"></a>

ピンの差し込み、角度を確認した後、残りのピンも半田付けします。

基板のOLEDの端にある四角形のシルク印刷の部分に、高さ調整用のゴムシートを貼り付けます。

<a href="image/oled-rubber.jpg"><img width=300 height=200 src="image/oled-rubber.jpg"></a>

次にピンヘッダを取り付けたOLEDを基板に差し込んで、こちらもまずは1つのピンを半田付けします。

<a href="image/oled_soldering07.jpg"><img width=300 height=200 src="image/oled_soldering07.jpg"></a>

ケースに仮組みし、OLEDがトップケースにはまるか確認します。位置がずれている場合は基板をケースから外し、半田付けしたピンを加熱しながらOLEDの位置を微調整します。

<a href="image/oled_adjust.jpg"><img width=300 height=200 src="image/oled_adjust.jpg"></a>

位置が確認出来たら残りのピンを半田付けします。

---

#### ロータリーエンコーダ

ロータリーエンコーダは、はやしたろう様設計のTHQWGD001Cを採用しています。
はやしたろう様の組み立て説明も参考にしてください。
https://note.com/taro_hayashi/n/nf608af2136d1

※本製品の使用に関するTHQWGD001Cの問い合わせは、はやしたろう様には行わないでください。

##### タクトスイッチ

<a href="image/tactsw_soldering01.jpg"><img width=300 height=200 src="image/tactsw_soldering01.jpg"></a>

タクトスイッチを基板表面から奥まで差し込み、端子4か所を半田付けします。

<a href="image/encoder_soldering01.jpg"><img width=300 height=200 src="image/encoder_soldering01.jpg"></a>

##### EC10E1220503

EC10E1220503を基板表面から写真の向きに差し込み、半田付けします。

##### THQWGD001C

ホイール部を組み立てます。
ホイールの平らな面の側から軸を差し込みます。

<a href="image/THQWGD001C_01.jpg"><img width=300 height=200 src="image/THQWGD001C_01.jpg"></a>

軸の先端を先ほど半田付けしたロータリーエンコーダに差し込みます。

<a href="image/THQWGD001C_02.jpg"><img width=300 height=200 src="image/THQWGD001C_02.jpg"></a>

軸のキャップを取り付けます。
方向に気を付けてください。（裾が広がっている方がロータリーエンコーダ側になります）

<a href="image/THQWGD001C_03.jpg"><img width=300 height=200 src="image/THQWGD001C_03.jpg"></a>

右側カバーを被せ、足元のくぼみにナットを差し込み、基板反対側からM2x5mmのネジ2本をドライバーで取り付けます。

<a href="image/THQWGD001C_04.jpg"><img width=300 height=200 src="image/THQWGD001C_04.jpg"></a>

左側カバーを上から差し込みます。

<a href="image/THQWGD001C_05.jpg"><img width=300 height=200 src="image/THQWGD001C_05.jpg"></a>

---

### ケースへの組み込み

#### 基板の取り付け

ボトムケースにUSB-Cのコネクタがある側から基板を差し込むように取り付けます。

#### OLED保護シートの除去

基板を取り付けたらOLEDの保護シートをはがします。

#### トップケースの取り付け

トップケースをはめ込み、ケース上面の穴4か所にM2x10mmのキャップボルトを差し込み、六角レンチで取り付けます。

<a href="image/case_01.jpg"><img width=300 height=200 src="image/case_01.jpg"></a>

#### ゴム足の貼り付け

ボトムケース裏面の四隅にゴム足を貼り付けます。

<a href="image/case_02.jpg"><img width=300 height=200 src="image/case_02.jpg"></a>

---

### キーの取り付け

キースイッチ10個をキーの向きに注意しながら差し込んでいきます。(ピン2本出ている側が本体OLED側になります)
取り付ける際に、キースイッチの足が曲がっているとうまくソケットにはまらないので、差し込む前に足がまっすぐになっているか確認し、曲がっている場合はラジオペンチなどでまっすぐになるように修正してください。

<a href="image/keysw_01.jpg"><img width=300 height=200 src="image/keysw_01.jpg"></a>

<a href="image/keysw_02.jpg"><img width=300 height=200 src="image/keysw_02.jpg"></a>

キースイッチを取り付けたらキーキャップを差し込んでいきます。

<a href="image/keycap_01.jpg"><img width=300 height=200 src="image/keycap_01.jpg"></a>

---

## ファームウェアの書き込み

ファームウェアファイル(morisoba_bitdeck10_via.uf2)を下記からダウンロードしてください。

https://github.com/morisobaR/BitDeck10/raw/refs/heads/main/firmware/morisoba_bitdeck10_via.uf2

ファームウェアの書き込みモードに入るには、本体裏のBOOTボタンをつまようじなどで押しながらUSBケーブルでPCに差し込んでください。
既にPCと接続済みの場合は、BOOTボタンを押しながらRESETボタンを押すとファームウェアの書き込みモードに入ることができます。

ファームウェアの書き込みモードに入るとPC上に外部ディスクとして認識されます。

<img src="image/RPi.png">

※上記Windowsの例ではFドライブに割り当たっていますが、お使いの環境によって異なります。

ファームウェアファイル(*.uf2)をこのドライブにコピーするとファームウェアが更新され、BitDeck10がリセットされ、キーボードのロゴがOLEDに表示されます。

---

## デフォルトのキーマップ

デフォルトのファームウェアではレイヤーが４つ用意されています。
右端の上下２ボタンにレイヤー切り替えが設定されており、BASE↔LOWER↔RAISE↔ADJUST↔BASEの順、および逆順で移動できるようになっています。

各レイヤーのキーマップはそれぞれ以下のように定義されています。
（デフォルトのキーマップについては予告なく変更する場合がございます。）

### レイヤー0 (BASE)

一般的なテキスト編集を想定したキーマップ

<table style="border: 1px solid;">
  <tr>
    <td width="150">COPY<br/>CTRL + C</td>
    <td width="150">PASTE<br/>CTRL + V</td>
    <td width="150">UNDO<br/>CTRL + Z</td>
    <td width="150">REDO<br/>CTRL + Y</td>
    <td width="150">ADJUSTレイヤーへ</td>
  </tr>
  <tr>
    <td width="150">全選択<br/>CTRL + A</td>
    <td width="150">単語選択<br/>CTRL + SHIFT + →</td>
    <td width="150">単語の先頭に移動<br/>CTRL + ←</td>
    <td width="150">次の単語に移動<br/>CTRL + →</td>
    <td width="150">LOWERレイヤーへ</td>
  </tr>
</table>

### レイヤー1 (LOWER)

ブラウザ操作を想定したキーマップ

<table style="border: 1px solid;">
  <tr>
    <td width="150">再読み込み<br/>メディアキー(WREF)</td>
    <td width="150">URLバーへカーソル移動<br/>CTRL + L</td>
    <td width="150">前ページへ<br/>メディアキー(WBAK)</td>
    <td width="150">次ページへ<br/>メディアキー(WFWD)</td>
    <td width="150">BASEレイヤーへ</td>
  </tr>
  <tr>
    <td width="150">新規タブ<br/>CTRL + T</td>
    <td width="150">タブを閉じる<br/>CTRL + W</td>
    <td width="150">前タブに移動<br/>CTRL + SHIFT + TAB</td>
    <td width="150">次タブに移動<br/>CTRL + TAB</td>
    <td width="150">RAISEレイヤーへ</td>
  </tr>
</table>

### レイヤー2 (RAISE)

YouTube視聴を想定したキーマップ

<table style="border: 1px solid;">
  <tr>
    <td width="150">再生/停止<br/>メディアキー(WPLY)</td>
    <td width="150">ミニプレイヤー<br/>I</td>
    <td width="150">5秒戻る<br/>←</td>
    <td width="150">5秒進む<br/>→</td>
    <td width="150">LOWERレイヤーへ</td>
  </tr>
  <tr>
    <td width="150">字幕<br/>C</td>
    <td width="150">全画面<br/>F</td>
    <td width="150">再生速度－<br/>SHIFT + ,</td>
    <td width="150">再生速度＋<br/>SHIFT + .</td>
    <td width="150">ADJUSTレイヤーへ</td>
  </tr>
</table>

### レイヤー3 (ADJUST)

Excelを想定したキーマップ

<table style="border: 1px solid;">
  <tr>
    <td width="150">COPY<br/>CTRL + C</td>
    <td width="150">PASTE<br/>CTRL + V</td>
    <td width="150">UNDO<br/>CTRL + Z</td>
    <td width="150">REDO<br/>CTRL + Y</td>
    <td width="150">RAISEレイヤーへ</td>
  </tr>
  <tr>
    <td width="150">合計※<br/>ALT + SHIFT + -</td>
    <td width="150">値の貼り付け<br/>CTRL + SHIFT + V</td>
    <td width="150">前シートに移動<br/>CTRL + PGUP</td>
    <td width="150">次シートに移動<br/>CTRL + PGDN</td>
    <td width="150">BASEレイヤーへ</td>
  </tr>
</table>
※「合計」操作については日本語キーボードを前提とした設定になっています。

---

### ロータリーエンコーダ

ロータリーエンコーダは全レイヤー共通でボリューム操作、押し込みでミュート切り替えになっています。

---

## キーマップの変更方法

キーマップはRemapやQMK Firmwareを書き換えることによって変更することができます。
Remapについてはブラウザ上で手軽にキーマップを変更することができます。
QMK FirmwareについてはC言語の知識が必要ですが、複雑なキーマップやマクロの定義、OLEDの表示内容など、比較的自由なカスタマイズが可能となります。

---

### Remap

#### 事前準備

* USBケーブルで本製品をPCに接続します
* 最新のRemap対応ブラウザ（Google Chrome または Microsoft Edge）を使用してください

#### Remapにアクセス

下記のURLにアクセスします：

[https://remap-keys.app](https://remap-keys.app)


#### Remapへのキーボードの接続

1. 「キーボードをカスタマイズ」をクリック
2. 表示されたデバイス一覧から本製品を選択

※接続時に「Please import your morisoba/bitdeck10 definition file(.json).」と表示された場合は、下記ファイルをRemapにインポートしてください。

https://github.com/morisobaR/BitDeck10/blob/main/firmware/bitdeck10/keymaps/via/via.json

#### キーマップの変更

接続が完了すると、現在のキー配置が表示されます。

* 画面下部のキー一覧からキーへドラッグ＆ドロップするか、各キーをクリックすると割り当てを変更できます
* 数字キー、ショートカット、レイヤー切替などを設定可能です
* ロータリーエンコーダの回転・押し込み動作も設定できます
* レイヤーは最大7つまで設定できます

#### 設定の書き込み

設定後、画面右上の「書き込み」ボタンをクリックすると、キーボードに書き込まれます。
書き込み完了後は、すぐに新しいキーマップが有効になります。

キーマップはキーボード本体に記録されるので、そのまま他のPC等へ接続しても追加のドライバ等が無くても利用できます。

---

### QMK Firmware

ファームウェアの変更にはQMK Firmwareのビルド環境が必要になります。
詳細についてはQMK Firmware関連のドキュメントを参照してください。

本製品のファームウェアのソースについては下記を参照してください。

https://github.com/morisobaR/BitDeck10/tree/main/firmware/bitdeck10

---

## OLED表示

OLEDの表示内容はファームウェア側で制御されています。
OLEDにはBitDeck10のロゴ表示の他に、キーの押下状態、ロータリーエンコーダの操作状態、現在のレイヤーと押下されたキーコードが表示されます。

しばらく操作を行わないと、次の操作までOLEDはOFFになります。

<img src="image/oled_display.png">

ロータリーエンコーダのステータスは以下のように表示されます。

<img src="image/encoder_status.png">

レイヤー表示は以下のようになります。

 0. BASE
 1. LOWER
 2. RAISE
 3. ADJUST

4番レイヤー以降を使用した場合は "LAYER_{レイヤー番号}" の表記になります。

キーコード表示についてはQMK FirmwareのKeycode Stringの内容に従います。

https://docs.qmk.fm/unit_testing#keycode-string
https://github.com/qmk/qmk_firmware/blob/master/quantum/keycode_string.c

※OLED表示のカスタマイズはファームウェアの変更が必要です

---

## 謝辞

本製品には、はやしたろう様作のTHQWGD001を利用させていただいております。
素晴らしい設計を公開していただき感謝いたします。

https://github.com/Taro-Hayashi/THQWGD001

https://note.com/taro_hayashi/n/nf608af2136d1

