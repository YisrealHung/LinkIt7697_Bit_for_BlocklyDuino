# LinkIt7697 Bit for BlocklyDuino
簡要說明
* 本擴充做為測試用途，有興趣的朋友請自行取用，使用到的程式庫版權歸原作者所有。
* 主要針對使用LinkIt7697，並結合LinkIt7697 Bit 安裝在MoonCar 上的應用，適合想要使用BlocklyDuino 來撰寫程式，控制MoonCar 的使用者。
* 擴充的部份主要是針對MoonCar 與LinkIt7697 Bit 上有的感測器與驅動裝置。
* 程式庫的部份，幾乎沿用BlocklyDuino 內建的程式庫，唯TCS34725是另外安裝的程式庫。在此將各功能整合並方便使用者操作而集合在一個欄位內。因WS2812 與OLED 在BlockylyDuino 已有適合的積木，故只類似超連結般放在欄位內方便使用，與從原來欄位使用是一樣的功能。

使用說明
* 首先下載並解壓縮BlocklyDuino V3 主程式，測試用版本是下載blocklyduino-3.0.312b-win64-ide.zip，連結如下：
https://github.com/MediaTek-Labs/BlocklyDuino-for-LinkIt/releases/tag/3.0.312b
* 將arduino-1.8.5 與package.nw 兩資料夾連同內部檔案直接複製到BlocklyDuino3 資料夾內並覆蓋檔案，即可在積木欄內看到MoonCar(登月小車)欄位。
