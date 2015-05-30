# pd2-2048

F74036352 資訊系 雷承勳

在QT介面上，先將1格label，放入格子的圖片，再將16個label擺放整齊，準備之後的2048運行時，遊戲的介面。

程式方面，於mainwindow.cpp中，有著init()，將介面初始化，bornpicture()產生最開始的兩個圖片，以及keyPressEvent(QKeyEvent *e)，
對使用者按下的按鍵作出相對應的反應，使圖形於正確位置產生或是改變。
設置遊戲結束時，會跳出Game Over的圖片，玩到出現2048時，會跳出You Win的圖片。
設置ReStart的按鈕，按下會使遊戲重新開始，可在遊戲結束時，或是遊戲進行中按下，皆會重新遊戲。
設置Exit的按鈕，按下將使遊戲介面關閉，離開遊戲。
設置記分板，計算當前分數，遊戲重新開始後，分數會歸零。

遊戲操作:
W->往上
S->往下
A->往左
D->往右
UML及截圖部分請看GITHUB中的UML.docx檔
