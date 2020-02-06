# LinkIt7697 Bit for BlocklyDuino
簡要說明
* 本擴充做為測試用途，有興趣的朋友請自行取用，使用到的相關程式庫版權歸原作者所有。
* 主要針對使用LinkIt7697，並結合LinkIt7697 Bit 安裝在MoonCar 上的應用，適合想要使用BlocklyDuino 來撰寫程式，控制MoonCar 的使用者。
* 擴充的部份主要是針對MoonCar 與LinkIt7697 Bit 上有的感測器與驅動裝置。
* 程式庫的部份，幾乎沿用BlocklyDuino 內建的程式庫，唯TCS34725是另外安裝的程式庫。在此將各功能整合並方便使用者操作而集合在一個欄位內。
* 因WS2812 與OLED 在BlockylyDuino 已有適合的積木，故只類似超連結般放在欄位內方便使用，與從原來欄位使用是一樣的功能。
<p align="center">
  <img src="https://github.com/YisrealHung/LinkIt7697_Bit_for_BlocklyDuino/blob/master/bit.png" width="700"/>
</p>

# 使用說明
* 首先下載並解壓縮BlocklyDuino V3 主程式，測試用版本是下載blocklyduino-3.0.312b-win64-ide.zip，連結如下：
https://github.com/MediaTek-Labs/BlocklyDuino-for-LinkIt/releases/tag/3.0.312b
* 將本Github上的檔案全部下載到自己的電腦，點選綠底白字的Clone or download，再點選Download ZIP。
* 將arduino-1.8.5 與package.nw 兩資料夾連同內部檔案直接複製到BlocklyDuino3 資料夾內並覆蓋檔案，即可在積木欄內看到MoonCar(登月小車)欄位。
<p align="center">
  <img src="https://github.com/YisrealHung/LinkIt7697_Bit_for_BlocklyDuino/blob/master/blockly.png" width="700"/>
</p>

# 各功能簡要範例說明
範例程式在example資料夾，打開BlocklyDuino3 並按下右上角有個資料夾圖案(開啟)，找到想要開啟的範例程式即可打開。範例程式名稱對應的功能如下:
* AB_button - A按鈕與B按鈕的使用
* Avoidance - 超音波距離感測器避障
* IR_read - 紅外線遙控器訊號讀取
* IR_send - 紅外線訊號發送
* OLED - OLED螢幕顯示文字
* RGB_LED - 魔幻LED使用方式
* color_sensor1 - 顏色感測器讀取RGB顏色通道
* color_sensor2 - 顏色感測器紀錄顏色與比對
* face_OLED - OLED顯示表情(共9種)
* line_follower - 循線(黑色線)範例
* motor_control1 - 移動控制(方法1)
* motor_control2 - 移動控制(方法2)

<p align="center">
  <img src="https://github.com/YisrealHung/LinkIt7697_Bit_for_BlocklyDuino/blob/master/mooncar.png" width="700"/>
</p>
