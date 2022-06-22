# OSGB_OfflineSmallGamesBox
 OSGB-OfflineSmallGamesBox Android App project for app102 course

## 最終成品
### [影片介紹](https://drive.google.com/drive/folders/1Wgoo9jEvUHA7wmcM3SpSBd8rJSQHi8bA?usp=sharing)
### [最終版APK檔案](https://drive.google.com/drive/folders/1Wgj5p0vv5j078GGDb01hH3oJwKlUj2Jk?usp=sharing)

## 安裝方式(建置專案步驟)
1. 請先確定您的電腦上有安裝[Node.js](https://nodejs.org/en/)

2. 請於Command Line執行以下指令安裝Cordova執行套件
```
npm install -g cordova
```

3. cd 進入```OSGB_cordovaPack```後執行以下指令來安裝專案相依套件
```
npm install
```

4. 請參考[Cordova官方Android編譯環境安裝指南](https://cordova.apache.org/docs/en/11.x/guide/platforms/android/index.html)，**仔細的一步步將 JDK、Gradle與Android SDK變數設定好!**

5. 接著執行以下指令來設定Android專案打包設定
```
cordova platform add android
```

6. 最後執行以下指令來建置專案
```
cordova build android
```

## Game List (預計要整合為App的小遊戲)

+ [Core Protection](https://github.com/hakimel/Core)

+ [2048](https://github.com/gd4Ark/2048)

+ [打磚塊、迷宮、疊疊樂等小遊戲](https://github.com/16Yongjin/html-games)

+ [動物連連看](https://github.com/gd4Ark/linkup)

+ [HexGL-3D飛船](https://github.com/BKcore/HexGL)

+ [Particle Clicker](https://github.com/particle-clicker/particle-clicker)

+ [Pac-Man](https://github.com/luciopanepinto/pacman)

+ [Tetris](https://github.com/luciopanepinto/tetris)

+ [記憶翻翻樂Memory-Game---Game-of-Thrones](https://github.com/KewinBielecki/Memory-Game---Game-of-Thrones)

+ [國旗顏色考驗](https://github.com/wentingliuu/flag-quiz-game) (要build可能比較麻煩，有可能遇到config設定問題)