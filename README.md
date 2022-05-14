# CkesStreamPlayer

使用 OvenMediaEngine(https://www.ovenmediaengine.com/) 架設私有的串流伺服器。
如果在區網使用，還需要一個前端的網頁播放串流。

這個網頁app，使用官方的 OvenPlayer 函式庫，加上 vue 做一個簡單的網頁，
可以自動偵測私有伺服器目前是否正在串流，如果有就自動播放直播影片。
省下要一直 reload 網頁。

無任何安全措施，建議使用在區網，無直播時建議關閉 omg server。
