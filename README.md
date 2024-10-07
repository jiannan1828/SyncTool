# SyncTool
 <br>
首次撰寫，排版拙劣，請見諒
 <br>
一個用描述語言做的同步小工具 <br>
我因工作/上課時，常需要同步多方資料，但用了各種工具後，仍然無法滿足，<br>
於是乾脆自己來寫一個利用windows10內建的同步的小工具: Robocopy.exe <br>
相關的指令網路上很多，在此便不介紹。 <br>
 <br> <br>
這個是我的同步狀況: <br>
![圖1](https://github.com/jiannan1828/SyncTool/blob/main/SyncWithNetDrive.png)
 <br> <br>
而同步路徑的清單，由外部的純文字文件列舉: <br>
![圖2](https://github.com/jiannan1828/SyncTool/blob/main/ListPara.png)
 <br> <br>
舉一個例子，假如我在桌面建立了兩個資料夾，分別為: Source / Target <br>
於是便可在params.txt輸入這兩個路徑: <br>
![圖3](https://github.com/jiannan1828/SyncTool/blob/main/ParaSources.png)
 <br> <br>
然後執行程式後可以看到提示: <br>
需要指定給他 "來源" 與 "目標" <br>
![圖4](https://github.com/jiannan1828/SyncTool/blob/main/ExecuteState.png)
 <br> <br>
當選定了 "來源" 與 "目標" 後， <br>
會再次詢問是否開始進行同步: <br>
![圖5](https://github.com/jiannan1828/SyncTool/blob/main/SelectDone.png)
 <br> <br>
執行後，可以看到同步工具每分鐘檢查Source/Target資料夾狀況 <br>
![圖6](https://github.com/jiannan1828/SyncTool/blob/main/Status0.png)
 <br> <br>
若發現不一致，則會啟動自動比對與同步 <br>
![圖7](https://github.com/jiannan1828/SyncTool/blob/main/Status1.png)
 <br> <br>


