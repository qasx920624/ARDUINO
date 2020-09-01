# ARDUINO
learn arduino
學習基礎ARDUINO 的程式設計
pinMode  腳位模式
pinMode (腳位,OUTPUT)
arduino 1. 讓LED 暗0.5S 充0.5S (閃爍)
void setup()----->只執行一次,arduino 的初始設定
void loop()------>重複執行,主程式位置
第一個指令
pinMode(腳位,INPUT/OUTPUT);
腳位模式設定 設定輸入或輸出
初始值是0

------------------------------------------------------

第一個程式(LED閃爍
void loop()
{
  digitalWrite(腳位,HIGH);
  delay(500);
  digitalWrite(腳位,LOW);
  delay;
}

if OUTPUT 輸出 LOW----->二極體有導通(發亮
if OUTPUT 輸出 HIGH---->二極體不導通(不亮
