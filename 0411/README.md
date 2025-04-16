# DevOps

## 升級 Gitlab 17 遇到的問題分析
Gitlab CI Runner 17 版綁定 token 的方式有所調整，探討如何進行升級。

## token 介紹
 
#### token 不同於 password 的地方
1. 不易偽造
2. 時效性
3. 系統產生 (高複雜度)
4. 不會產生到舊的、重複的 token
