# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能

## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
## TCP/IP有那些層?寫出與OSI七層模型的對應!

## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - HyperText Transfer Protocol 超文本傳輸協定
    - HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
    - HTTP是全球資訊網的數據通信的基礎。
  - HTTPS
    - 超文本傳輸安全協定（HyperText Transfer Protocol Secure，HTTPS；
    - 常稱為HTTP over TLS、HTTP over SSL或HTTP Secure
    - HTTPS是一種透過計算機網路進行安全通訊的傳輸協定。
    - HTTPS經由HTTP進行通訊，但利用SSL/TLS來加密封包。
    - HTTPS開發的主要目的，是提供對網站伺服器的身分認證，保護交換資料的隱私與完整性。 
- DNS vs DNSsec
 - DNS
   -網域名稱系統（英語：Domain Name System，DNS）
   -域名和IP位址相互對映的一個分散式資料庫，DNS使用TCP和UDP埠53[1]。
   -對於每一級域名長度的限制是63個字元，域名總長度則不能超過253個字元。
 - DNSsec
   -域名系統安全擴充（英語：Domain Name System Security Extensions，DNSSEC）
   -Internet工程任務組 （IETF）的對確保由域名系統 （DNS）中提供的關於網際網路協定（IP）網路使用特定類型的資訊規格套件
   -它是對DNS提供給DNS客戶端（解析器）的DNS資料來源進行認證，並驗證不存在性和校驗資料完整性驗證，但不提供機密性和可用性[1]。
- telnet vs ssh
 - telnet 
   -Telnet是一種應用層協定，使用於網際網路及區域網中，使用虛擬終端機的形式，提供雙向、以文字字串為主的命令列介面互動功能
   -屬於TCP/IP協定族的其中之一，是網際網路遠端登錄服務的標準協定和主要方式
   -常用於伺服器的遠端控制，可供使用者在本地主機執行遠端主機上的工作
 - ssh
   -安全外殼協定（Secure Shell Protocol，SSH）是一種加密的網路傳輸協定，可在不安全的網路中為網路服務提供安全的傳輸環境[1]
   -SSH通過在網路中建立安全隧道來實現SSH客戶端與伺服器之間的連接[2]。
   -SSH最常見的用途是遠端登入系統，人們通常利用SSH來傳輸命令列介面和遠端執行命令
   -SSH使用頻率最高的場合是類Unix系統，但是Windows作業系統也能有限度地使用SSh
- ftp vs sftp


- smtp, pop3
- SNMP

## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
  - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
- IP
- ICMP
