# 雜項簡介

Misc 是英文 Miscellaneous 的前四個字母，雜項、混合體、大雜燴的意思。

Misc 在國外的比賽中其實又被具體劃分爲各個小塊，有

-   Recon
-   Forensic
-   Stego
-   Misc
-   ……

在國內的比賽中，被統一劃分入 Misc 領域，有時 Crypto（尤其是古典密碼）也被劃入其中。

在 Misc 這一章節中，將從以下幾個方面介紹這一塊的知識：

-   Recon（信息蒐集）

    主要介紹一些獲取信息的渠道和一些利用百度、谷歌等搜索引擎的技巧

-   Encode（編碼轉換）

    主要介紹在 CTF 比賽中一些常見的編碼形式以及轉換的技巧和常見方式

-   Forensic && Stego（數字取證 && 隱寫分析）

    隱寫取證是 Misc 中最爲重要的一塊，包括文件分析、隱寫、內存鏡像分析和流量抓包分析等等，涉及巧妙的編碼、隱藏數據、層層嵌套的文件中的文件，靈活利用搜索引擎獲取所需要的信息等等。

CTF 中 Misc 與現實中的取證不同，現實中的取證很少會涉及巧妙的編碼加密，數據隱藏，被分散嵌套在各處的文件字符串，或是其他腦洞類的
Challenge。很多時候是去精心恢復一個殘損的文件，挖掘損壞硬盤中的蛛絲馬跡,或者從內存鏡像中抽取有用的信息。

現實的取證需要從業者能夠找出間接的惡意行爲證據：攻擊者攻擊系統的痕跡，或是內部威脅行爲的痕跡。實際工作中計算機取證大部分是從日誌、內存、文件系統中找出犯罪線索，並找出與文件或文件系統中數據的關係。而流量取證比起內容數據的分析，更注重元數據的分析，也就是當前不同端點間常用 TLS 加密的網絡會話。

Misc 是切入 CTF 競賽領域、培養興趣的最佳入口。Misc 考察基本知識，對安全技能的各個層面都有不同程度的涉及，可以在很大程度上啓發思維。

![](figure/all.png)