FairyGUI helpbook
### 相關教程
 - 金波資料交換暫存區 - FairyGUI-Tutorial
### 環境設置
::: info 
注意:若在fairyGUI官網下載SDK(laya版)，請確認Branch版本(選layaair2.0-2.1)
:::
![](https://i.imgur.com/JTYRpE3.png)

----
### 3.10版以上
安裝後，第一次設置project時，可刪除多餘檔案，將assets, settings, fairy, FGUIDemo等資料夾。
### git 上架結構
專案下設置3個目錄, 分別為:
> DragonBone
> >:::info
> >(設計完成的龍骨)置於NAS，修改以資料夾命名日期，並通知專案TA，一律由TA 做版控上傳Git
> >
> fgui
> > :::info
> >工作檔上傳至dev branch(fgui目錄下)
> >
> laya
> >:::info
> > 管理 ． laya (TA若有需求, 可與前端溝通新增branch)

----

### 關聯設置方式
:::info 父子層級概念:
先選子物件，指定關聯父物件，便可定義其關係; 父層級移動，子層級按定義關係相對移動
:::
**TA應用**
|選廳頁|規格|
|:---|---|
|荷官(龍骨動畫)|容器組件, 左右居中, 底底(9/24修訂)|

|主遊戲場景|規格|
|:---|---|
|牌局編號及底分 |對齊左上角功能鍵  |

----
### 圖片
- **Mask**
ex:如欲達到光暈遮罩
![](https://i.imgur.com/Le1Lriw.gif "ex:如欲達到光暈遮罩")

點選空白處，於「基本設置」內設定「自定義遮罩」(選遮罩物件)
![](https://i.imgur.com/LnZtgQa.png)

- 透明度
可於「基本」設置透明度
- Anchor
人像圖片設中心「錨點」:
由於前端可能需要派獎(動畫)跑向人像中心，故採此做法

       {anchor="true" }


