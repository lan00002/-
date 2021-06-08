# -資財二乙 1080708 藍士翔

#起源：
發布程式的Exchange漏洞「ProxyLogon」有關，許多組織藉此來攻擊，而這臺伺服器後來被駭客當作C&C中繼站使用，導致接下來發生加密攻擊事故，而傳出微軟對合作的資安業者著手調查的風聲，甚至傳出勒索軟體攻擊事件駭客入侵受害單位的管道，就是鎖定尚未修補漏洞的Exchange伺服器。

#嚴重性：
使用Exchange Server的大多是政府及大型公司。Exchange Sever被駭客攻擊，竊取登入，會對企業造成非常大的損失，且擴大至植入挖礦程式與勒索。根據資安業者ESET的統計，至少有10組以上的駭客鎖定ProxyLogon漏洞展開攻擊。

#改善：
微軟發布修補的Exchange漏洞ProxyLogon，經過近一個月持續推出各式的解決工具，逾9成Exchange伺服器已完成ProxyLogon修補。

#個人觀點：
駭客在繞過身分認證後，利用這個漏洞建立web shells或將身份升級至SYSTEM後，達到竊取郵件的目的
此漏洞已被中國政府的駭客組織Hafnium使用，被放入Webshell自動入侵的後門程式，已經流失的資料已經超乎想像
如果遭受攻擊，要立即與資安防範小組聯絡
