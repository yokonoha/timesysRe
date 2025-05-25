# ⌚timesysRe  
*********************
[!TIP]
↓Translations (Chinese is by Machine translation)  

[English](./en.md) || [Chinese(simplified)](./cn.md) || [Chinese(Traditional)](./cn2.md)  
*********************
Time display System script (Recreated) Rev.2
使いやすい時刻表示スクリプト   

### 🆕New!  
Rev.2より、12時間表示とAM/PM表記に対応しました!  
Rev.2.5より、周(中国語表記2つ目)にも対応しました。  
### About Licenses
ライセンスはありませんが著作権は横茶横葉が保持しています。  
横茶横葉の利用規約に従ったうえで、ご自由にご活用ください。  
利用規約へはメインサイトのfooterからアクセスできます。  
https://yokonoha.github.io/  
(利用規約要点抜粋→このコンポーネントを使用したことによるすべての事柄において製作者は一切の責任を負いかねます。)  
他のリポジトリではこのtimesysre.jsに対してMITライセンスや横茶横葉独自ライセンスを適用している場合がありますが、このリポジトリからダウンロードしたものに関しては適用されませんのでご安心ください!  
クレジット表記はしていただければとてもうれしいですが、書きたくないよという方は書かなくてもOKです。  
## 実装用チートシート(timesysre内にも記載があります。)  
Apply!  
```html.html
<script src="timesysre.js"></script>
```
& Use!  
```usecase.html
<p><span id="year"></span>/<span id="month"></span>/<span id="date"></span></p>
<p id="day"></p>
<p><span id="hour"></span>:<span id="min"></span> <small><span id="sec"></span></small></p>
```
プレビュー  
2025/02/20  
Thursday  
16:32 45  

### 🆔Available IDs  
// year: 年のみ代入  
//month: 月のみ代入  
// date: 日のみ代入  
// hour: 時のみ代入  
//  min: 分のみ代入  
//  sec:秒のみ代入  
//  day:曜日のみ代入  
//youbi:日本語表記での曜日を代入 
// zhou:周(中国語) 
//xingqi:星期(中国語)  

(Rev2から対応)
// ampm: AM/PMのみ代入
// hour2: 12時間制の時のみ代入

***************************
©2025 横茶横葉 All Rights Reserved.  
©2025 横葉の工房 All Rights Reserved.    
