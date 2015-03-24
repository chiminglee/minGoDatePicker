# minGoDatePicker
datepicker for default and Chinese datepicker

在台灣的公家或教育單位，應該很常面臨類似的問題 - 行政人員習慣輸入民國年日期，但我們資料庫的datetime是西元年的。

以前會採用轉來轉去的方式，讓行政人員輸入民國年 ( ex. 1040324 )，到後端轉為伺服器用的日期 ( ex. 2015-03-24 20:08:00 )，
現在又進步到有小套件的協助，不用輸入，用點選的，但問題就在於jquery ui的datepicker預設西元年，要想辦法弄成民國年實在很頭痛。

找了很久，也想盡辦法看原始碼，終於弄出解法，希望有幫助到需要民國年的人。

範例: <a href="http://www.cc.ncu.edu.tw/~center61/minGoDatePicker/mingo.html" target="_blank">連結</a>
