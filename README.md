# SyncTool
一個用描述語言做的同步小工具

我因工作/上課時，常需要同步多方資料，但用了各種工具後，仍然無法滿足，
於是乾脆自己來寫一個利用windows10內建的同步的小工具: Robocopy.exe
相關的指令網路上很多，在此便不介紹。



這個是我同步的狀況:

![圖1](https://github.com/jiannan1828/SyncTool/blob/main/SyncWithNetDrive.png)



而同步路徑的清單，由外部的純文字文件列舉:

![圖2](https://github.com/jiannan1828/SyncTool/blob/main/ListPara.png)



舉一個例子，假如我在桌面建立了兩個資料夾，分別為: Source / Target
於是便可在params.txt輸入這兩個路徑:

![圖3](https://github.com/jiannan1828/SyncTool/blob/main/ParaSources.png)



然後執行程式後可以看到提示:
需要你指令 "來源" 與 "目標"

![圖4](https://github.com/jiannan1828/SyncTool/blob/main/ExecuteState.png)



當選定了 "來源" 與 "目標" 後，
會再次詢問是否開始進行同步:

![圖5](https://github.com/jiannan1828/SyncTool/blob/main/SelectDone.png)



執行後，可以看到同步工具每分鐘檢查Source/Target資料夾狀況

![圖6](https://github.com/jiannan1828/SyncTool/blob/main/Status0.png)



若發現不一致，則會啟動自動比對與同步

![圖7](https://github.com/jiannan1828/SyncTool/blob/main/Status1.png)



