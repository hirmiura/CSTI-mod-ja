# CSTI-mod-ja

これは[Card Survival: Tropical Island] (以下CSTI)の日本語翻訳を更新する為のModです。

## 最新版について

以下よりダウンロードしてください。  
https://raw.githubusercontent.com/hirmiura/CSTI-mod-ja/main/updated/Jp.csv

## インストール

`{CSTIのホーム}/Card Survival - Tropical Island_Data/StreamingAssets/Localization/Jp.csv` に本Modの `Jp.csv` を上書きしてください。  
ゲームを実行中の場合は、ゲームを再起動すると反映されます。

## アンインストール

上記でインストールしたファイルを削除し、バックアップ済みのオリジナルに戻してください。  
Steamであれば、ファイルを消してから「ゲームファイルの整合性を確認」をするのが楽です。

## 変更点

クローンしている場合は、以下のコマンドで見ることができます。

```bash
git diff HEAD:original/Jp.csv HEAD:updated/Jp.csv
```

次のURLで見られれば良かったのですが、この機能はないようです。  
https://github.com/hirmiura/CSTI-mod-ja/compare/HEAD:original/Jp.csv...HEAD:updated/Jp.csv

### 主な変更点

* 地名
  * Bay → 入江 で統一
  * Bearch → ビーチ で統一

* 貯水
  * Water Reservoir → 貯水槽 で統一
  * Cistern → 貯水池 で統一

* 植物
  * Snake grass → [クリナカンサス](https://en.wikipedia.org/wiki/Clinacanthus_nutans)  
    「クリナンカスヌタンス」や「マムシグサ」と表記揺れがあった
  * Spider lilly → [ササガニユリ](https://en.wikipedia.org/wiki/Hymenocallis_speciosa)  
    彼岸花のイメージと明らかに違った
  * China rose → ハイビスカス  
    コウシンバラとあったが、アイコンが明らかにハイビスカスだった

* その他
  * 昼寝 → 仮眠
  * バッター → バター
  * 他多数

## ライセンス

[MIT License] としています。  
ご自由にお使いください。

---

[Card Survival: Tropical Island]: https://store.steampowered.com/app/1694420/Card_Survival_Tropical_Island/
[MIT License]: https://opensource.org/license/mit/
