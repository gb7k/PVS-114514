# PVS-114514 DIY Night Vision Housing
## はじめに
PVS-114514は3Dプリンタで作成するマニュアルゲイン機能を備えたDIY Night Vision Housingである。  
今までも海外などで3Dプリンタ製のハウジングは存在したが、pigtailの付いていないMX-10160のものばかりであった。  
そこで今回、pigtailが付いたMX-11769/UVに対応したハウジングの試作を実施した。  
また、このハウジングはPVS-14の対物レンズが装着可能となっている。

<img alt="NOD" src="https://github.com/user-attachments/assets/c0770f83-344c-498c-9bcd-d7fe0fae0cc9" width="450px">
<img alt="NOD" src="https://github.com/user-attachments/assets/1f0fdb93-3ddc-400b-949f-e889eac5f7f9" width="450px">

## 概要
本装置を作成するにあたり、はんだ付け,圧着,3Dプリント,接着といった作業を実施する必要がある。  
また今回も再現する人が出てこないと踏んでいるため、かなりの部分を省いて記載している。  
詳細が必要であれば何かしらでご連絡ください。

## お断り
高価な増幅管を使用するので自作の場合はくれぐれも自己責任で電源を投入すること。  
逆接、半田ブリッジ等で増幅管に負荷がかかり使用出来なくなった等の責任は負えません。

## 必要な工程
|番号|工程|備考|
| --- | --- | --- |
|1|部材の調達|インターネットやリアル店舗を使用|
|2|基板の作成|基板をはんだ付け|
|3|配線|基板へつなげるコネクタの作成|
|4|3Dプリント|筐体を作成する|
|5|組み立て|すべてを結合する|

## 必要な部材
電子部品は千石電商とマルツで揃う。  
今回は試作品というのもあり基板はユニバーサル基板を使用している。  
個々にある部材と同じものが手に入らなくても同等品が手に入ればOK(特に電子部品)
|部材名称|個数|型式|
| --- | --- | --- |
|接眼レンズ用ルーペ|1|シンワ測定 75571|
|プッシュスイッチ|1|DS-282-R|
|200kΩ可変抵抗|1|RK1631110-K15-C0-B204-L|
|リード線付きCR123A電池ボックス|1|CR123A-R|
|ユニバーサル基板|1|SYJ-2036|
|ユニバーサル基板|1|TNF 15-25|
|スプリングピン|1|SYJ-2036(5個入)|
|ショットキーバリアダイオード|1|30GQA03L|
|ICソケット|1|平ピン 8P|
|XHコネクタ ベース付きポスト 2pin|1|B2B-XH-A(LF)(SN)|
|XHコネクタ ベース付きポスト 3pin|1|B3B-XH-A(LF)(SN)|
|XHコネクタ ベース付きポスト 4pin|1|B4B-XH-A(LF)(SN)|
|XHコネクタ ハウジング 2pin|1|XHP-2|
|XHコネクタ ハウジング 3pin|1|XHP-3|
|XHコネクタ ハウジング 4pin|1|XHP-4|
|結束バンド|1|KBR-N200010|
|基板固定用M3タッピングナベネジ|2| |
|電池固定用M3タッピング皿ネジ|2| |

## 基板製作
**作成中**  

実基板  
<img alt="NOD" src="https://github.com/user-attachments/assets/a037b29c-3c35-4467-b964-27f54653f270" width="450px">  

配線図 基板表  
<img alt="NOD" src="https://github.com/user-attachments/assets/337d60a8-89f9-403b-8fe1-774203642d2f" width="450px">  
配線図 基板裏  
<img alt="NOD" src="https://github.com/user-attachments/assets/26428529-20c9-4c2f-b153-efd72d81fe3c" width="450px">  
増幅管基板  
<img alt="NOD" src="https://github.com/user-attachments/assets/faea16d6-fcc6-4d68-8e0b-a98d5c92c78e" width="450px">  

動作テスト  
<img alt="NOD" src="https://github.com/user-attachments/assets/62b47465-7fbe-4c03-bde1-2b44d0ca7ccf" width="450px">  


## 現在の問題点と今後の予定
- 基板剥き出しなのでカバーしたい。
    - 面倒でネジ穴を付けなかった
- ハウジングの接着
    - 一体型にしたかったけど結束バンド用穴の処理が面倒だった
- 管への電源供給基板の押さえ方
    - イイ感じの圧力でおさえる楽な方法が結束バンドだった、もっといい方法はあるはず
- ヘッドマウント
    - 強度がね……PA12GBとかで作るなら……。
- 防水性
    - そもそも印刷表面が荒いので防水性の担保が大変難しい
- ピンの入手性
    - ミニ四駆の金メッキターミナルとか流用出来ると良さそうだが……。
- マニュアルゲインが付いた双眼
    - もちろん作る予定、いつになるか分かりませんが……。
