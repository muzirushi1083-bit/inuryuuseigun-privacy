# inuryuuseigun-privacy

犬流星群を撮りに行こう！（Dog Meteors）のプライバシーポリシーとサポートページを公開するためだけのリポジトリ。

```
https://muzirushi1083-bit.github.io/inuryuuseigun-privacy/
https://muzirushi1083-bit.github.io/inuryuuseigun-privacy/support.html
```

Apple は提出時にこの URL へ実際にアクセスするので、**404 にしたら審査で落ちる。**

## 更新のしかた

原本（ゲーム本体の private リポジトリの `docs/inuryuuseigun/privacy-policy/`）を直してから、
このリポジトリに同じ3ファイルを push する。**上書きの前に原本・ここ・公開 URL の3つを diff する。**
Pages のビルドは1〜2分かかる。push 直後は 404 のままなので、待ってから確認すること。

> 他タイトルの `*-privacy` に相乗りさせないこと。URL に別アプリの名前が入る。

## 前作と内容が違う点（コピーして流用しないこと）

| 項目 | 善意の顔 | 犬流星群 |
|---|---|---|
| 広告 | AdMob（IDFA・ATT あり） | **無し** |
| 課金 | 「広告を消す」 | **無し**（買い切り） |
| 通信 | 広告のみ | **一切無し**（計測は送信しない） |
| 写真 | 触らない | **追加のみの許可**（保存）＋ **PHPicker**（選んだ1枚だけ取り込む） |
| 端末内のデータ | 音・問題数・購入状態 | 進行・設定・**アルバムの写真** |

App Privacy の申告は「データを収集しない」。
