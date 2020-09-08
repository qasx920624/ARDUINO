# ARDUINO 第一篇
learn arduino   </p>
學習基礎ARDUINO 的程式設計</p>
pinMode  腳位模式</p>
pinMode (腳位,OUTPUT)</p>
arduino 1. 讓LED 暗0.5S 充0.5S (閃爍)</p>
void setup()----->只執行一次,arduino 的初始設定</p>
void loop()------>重複執行,主程式位置</p>
第一個指令</p>
pinMode(腳位,INPUT/OUTPUT);</p>
腳位模式設定 設定輸入或輸出</p>
初始值是0</p>
</p>
</p>
</p>
第一個程式(LED閃爍</p>
```c++


void loop()
{
  digitalWrite(腳位,HIGH);
  delay(500);
  digitalWrite(腳位,LOW);
  delay;
}
```
</p>
if OUTPUT 輸出 LOW----->二極體有導通(發亮</p>
if OUTPUT 輸出 HIGH---->二極體不導通(不亮</p>

------------------------------------------------------
電路圖如下:
![image](https://github.com/qasx920624/ARDUINO/blob/master/DE7C66F1-AEA6-4C9A-8054-684F44AC2B0B.jpeg)
