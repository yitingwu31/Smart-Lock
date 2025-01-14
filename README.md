# Smart-Lock
A bicycle lock for laziness 

## Members
高偉堯 ([KaoWYK](https://github.com/KaoWYK))
陳俊廷 ([Jim-CTChen](https://github.com/Jim-CTChen))
吳宜庭 ([yitingwu31](https://github.com/yitingwu31))
黃善莛

## Description
有時候可能因為下雨而一手撐傘，或是剛買完活大的麥當勞飲料而只有一手可以使用，此時要開腳踏車的鎖就不太方便。所以我們想做一個可以單手開啟的腳踏車鎖。
鎖的設計參考路上的共享自行車，開鎖方式可以用手機中的App遙控控制或是利用RFID感應學生證來開鎖。另外我們利用霍爾感測器判斷腳踏車是否有被騎乘，如果停留長達一定的時間則會自動上鎖，這樣就不用擔心腳踏車忘記上鎖而被偷走。
另外車鎖上也附有能用手機App遙控的LED燈和蜂鳴器，協助晚上找車。

## Usage
1. 利用刷卡or手機藍芽單手開鎖，下雨天再也不用淋濕~
2. 忘記鎖車也可以自動上鎖喔^^
3. 晚上電路學實驗大家都亂停找不到車? 有蜂鳴器和LED怎麼可能還找不到～～

## Functions
1. RFID
    * 利用手機藍芽設定一張悠遊卡為key card
    * 刷卡後開鎖、閉鎖
2. BlueTooth
    * 開/關鎖 
    * 開/關LED燈 
    * 開/關蜂鳴器 
    * 設定key card
3. LED
    * 當車燈

## Materials
1. Arduino UNO
2. 麵包板、杜邦線
3. 蜂鳴器(喇叭)、藍芽(HC-05)、RFID(mfrc522)、LED、霍爾模組(KY-024)、步進馬達 + 擴充模板(IC: ULN2003)
4. 3D-print frame
5. 密集板
6. 電池模組
