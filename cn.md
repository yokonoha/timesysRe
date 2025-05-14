簡体中文（简体版）

Time display System script (Recreated) Rev.2
易于使用的时间显示脚本

新功能！

从 Rev.2 开始，支持12小时制和AM/PM标记！

关于许可

本脚本没有许可证，但版权归横茶横叶所有。
请遵循横茶横叶的使用条款自由使用。
可通过主网站的页脚访问使用条款。
https://yokonoha.github.io/readme
（使用条款要点摘录→开发者对因使用本组件引发的任何问题概不负责。）
其他仓库可能对该 timesysre.js 使用MIT许可证或横茶横叶自定义许可证，但请放心，从本仓库下载的版本不适用这些条款！
如果您愿意标注出处我们会非常感激，但如果不想标注也完全可以！  
## Examples  
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
### Available IDs  
// year: 年のみ代入  
//month: 月のみ代入  
// date: 日のみ代入  
// hour: 時のみ代入  
//  min: 分のみ代入  
//  sec:秒のみ代入  
//  day:曜日のみ代入  
//youbi:日本語表記での曜日を代入  
//xingqi:星期。(簡体字) -Beta(中国語(汉语)での表記にも対応しています。)  

(Rev2から対応)
// ampm: AM/PMのみ代入
// hour2: 12時間制の時のみ代入

***************************
©2025 横茶横葉 All Rights Reserved.  
©2025 横葉の工房 All Rights Reserved.    
