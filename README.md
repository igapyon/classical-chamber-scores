# classical-chamber-scores

室内楽のテスト用サンプルデータ（MuseScore形式）を管理するリポジトリです。

## 概要

- 目的: クラシック室内楽作品のテスト用サンプルスコアを `.mscz` 形式で管理する
- 現在の収録例: Mozart / String Quartet No.15 in D minor, K.421（各楽章）

## ディレクトリ構成

```text
.
├─ composers/
│  └─ Mozart/
│     ├─ Mozart_SQ_No15_K421_Mvt1.mscz
│     ├─ Mozart_SQ_No15_K421_Mvt2.mscz
│     ├─ Mozart_SQ_No15_K421_Mvt3.mscz
│     └─ Mozart_SQ_No15_K421_Mvt4.mscz
└─ LICENSE
```

## 使い方

1. MuseScore（推奨: 最新版）をインストールします。
2. 開きたい `.mscz` ファイルを MuseScore で開きます。
3. 必要に応じて PDF / MusicXML / MIDI へ書き出します。

## 命名ルール（現状）

- `Composer_Work_Movement.mscz`
- 例: `Mozart_SQ_No15_K421_Mvt1.mscz`

## ライセンス

このリポジトリは [LICENSE](LICENSE) に従います。
