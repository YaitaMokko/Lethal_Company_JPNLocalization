# Lethal Companyの日本語化方法について
Lethal Company日本語化について
## **注意**
このゲームは早期アクセスゲームです。予告なく仕様が変わるおそれがあります。  
**2023年11月12日**にリリースされた**Version 40**に対応したModです。  
## **インストール方法**
1.UnityにModを外部から当てるBepInExをここからダウンロードしてください。  
　[BepInEx_x64](https://github.com/BepInEx/BepInEx/releases/latest)   
　2023/12/03時点で最新は BepInEx_x64_5.4.22.0.zipです。  
2.ダウンロードしたBepInEx_x64を展開し、  
　メインゲームフォルダ(\Lethal Company)の下に全部インストールしてください。  
　BepInEx(フォルダ)/changelog.txt/doorstop_config.ini/winhttp.dll を  
　Lethal Company.exeと同じフォルダに入れてください。  
3.Lethal_CompanyにMod APIを提供するLC APIをここからダウンロードしてください。  
　[LC API](https://thunderstore.io/c/lethal-company/p/2018/LC_API/)  
 　2023/12/03時点で最新は 2018-LC_API-2.1.1.zipです。  
4.ダウンロードした2018-LC_API-XXX.zipを展開し、  
　BepInEx(フォルダ)/を Lethal Company.exeと同じフォルダに入れてください。  
5.ゲームに適用するフォントをここからダウンロードしてください。  
　[TMP_Font_AssetBundles.zip](https://github.com/bbepis/XUnity.AutoTranslator/releases)  
6.ダウンロードしたTMP_Font_AssetBundles.zipを展開し、  
　メインゲームフォルダ(\Lethal Company)の下に全部インストールしてください。  
　arialuni_sdf_u2019/arialuni_sdf_u2019を Lethal Company.exeと同じフォルダに入れてください。  
7.Lethal_Companyにターミナル編集機能を提供するNew Terminalをここからダウンロードしてください。  
　[New Terminal](https://thunderstore.io/c/lethal-company/p/Aavild/NewTerminal/)  
8.ダウンロードしたAavild-NewTerminal-xxx.zipを展開し、  
　メインゲームフォルダ(\Lethal Company)の下に全部インストールしてください。  
　BepInEx(フォルダ)/を Lethal Company.exeと同じフォルダに入れてください。  
9.Mokko-JPNLocalization-XXX.zipをここからダウンロードしてください。  
　[JPNLocalization](https://github.com/YaitaMokko/Lethal_Company_JPNLocalization/releases/latest)  
10.ダウンロードしたファイルを展開し、メインゲームフォルダ(\Lethal Company)の下に全部インストールしてください。  
　BepInEx(フォルダ)を Lethal Company.exeと同じフォルダに入れてください。  
以上。  

## **起動**
ゲームを起動しOnline(推奨)となっていれば日本語化完了です  
  
## **注意点**
ゲーム内の**アクセス端末**や**トレーニングマニュアル**は**英語**のままです。  
無理矢理日本語表示にしているため見にくい場所が多々あります。誰か直し方教えて…  
端末からコマンドを打つ方法などはこの方の日本語のマニュアルを参考にして下さい。  
[Steamガイド Lethal Company 遊び方](https://steamcommunity.com/sharedfiles/filedetails/?id=3078124672)  

## **詳細**  
中身はいたって単純で  
BepInEx\config\jpに翻訳ファイルを詰め込んでるだけです。  
```
Sprint: [Shift]=走る：[Shift]  
Open: [E]=開ける：[E]   
Turn on/off : [E]=ON/OFF：[E]  
Switch camera : [E]=カメラ切替：[E]  
```
みたいな感じ  
それをXUnity.AutoTranslatorに読み込ませて日本語を表示しています。  

## **その他**  
この翻訳ファイルについて権利は主張いたしません。配信等で使っていただいても問題ありません。  
権利は主張しませんが、本家が日本語対応した場合はそちらに切り替えるようお願いいたします。  

## **変更履歴**
1.1.1 2023/12/05 NewTerminal Mod使用でターミナル端末の日本語化追加  
1.1.0 2023/12/04 Release
