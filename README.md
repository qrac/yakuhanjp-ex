# Yaku Han JP - EX

## About

"Yaku Han JP EX"は、"[Yaku Han JP][link-yakuhanjp-repo]"の実験的なバージョンです。

## Detail

### YakuHanJP-EX-Emotion

YakuHanJP から感嘆符・疑問符を抜いたもの。Emotion とは無感情の意を表しています。ゴシック体のみ制作してみました。

## Valuation

### Include Fonts

- YakuHanJP-EX-Emotion

内包する文字はそれぞれ以下の通りです。

```
// YakuHanJP-EX-Emotion
、。〈〉《》「」『』【】〔〕・（）：；［］｛｝
```

※バグ回避のため、全てのフォントに `.notdef` `space` `ellipsis` が含まれています

### Font Weight

ウェイトは 7 段階。付属の CSS では以下の font-weight で指定できます。ベースフォント毎にウエイト・ファイル名が若干異なるため、当ライブラリ内のファイル名もそれぞれのベースフォントに準じています。

#### YakuHanJP-EX-Emotion

- font-weight: 100; // Thin
- font-weight: 200; // Light
- font-weight: 300; // DemiLight
- font-weight: 400; // Regular
- font-weight: 500; // Medium
- font-weight: 700; // Bold
- font-weight: 900; // Black

## Use

### [CDN][link-jsdelivr]

jsDelivr で配信している CSS ファイルへのリンクを HTML 内に記述するだけで全ウェイトのフォントを利用できます。

```html
// YakuHanJP-EX-Emotion
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/yakuhanjp-ex@0.1.0/dist/css/yakuhanjp-ex-emotion.min.css">
```

### [npm][link-npm]

npm コマンドで任意のプロジェクトにインストールできます。

```
npm install yakuhanjp-ex
```

### Download

1.  データを[ダウンロード][link-download]
2.  dist フォルダ内の「css」「fonts」を制作サイトに配置
3.  HTML 内で CSS を読み込む

- YakuHanJP-EX-Emotion
  - yakuhanjp-ex-emotion.min.css

4.  CSS でフォントを適応

- YakuHanJP-EX-Emotion
  - 「YakuHanJP-EX-Emotion」

```html
// YakuHanJP-EX-Emotion
<link rel="stylesheet" href="dist/css/yakuhanjp-ex-emotion.min.css">
```

```css
// YakuHanJP-EX-Emotion
.yakuhanjp-ex-emotion {
  font-family: YakuHanJP-EX-Emotion, "Hiragino Sans", Meiryo,
    "Yu Gothic Medium", sans-serif;
}
```

## Custom

### Font face

1.  利用するフォントファイルへのリンクを個別に取得（CDN の場合）

- [YakuHanJP-EX-Emotion](https://cdn.jsdelivr.net/npm/yakuhanjp-ex@0.1.0/dist/fonts/YakuHanJP-EX-Emotion/)

2.  CSS 内に font-face を記述

## Support

| Chrome | Firefox | IE  | Ege | Opera | Safari(Mac) |
| :----: | :-----: | :-: | :-: | :---: | :---------: |
|  55~   |   50~   | 9~  | 14~ |  36~  |     6~      |

| Safari(iOS) | Chrome(Android) | Browser(Android) |
| :---------: | :-------------: | :--------------: |
|     7~      |       51~       |       4.4~       |

## License

- Yaku Han JP EX : SIL OFL 1.1
- Author : [Qrac][link-twitter]
- Author Group: [QRANOKO][link-qranoko]
- Gothic fonts : Based on ["Noto Sans CJK JP"][link-notosans] licensed under the SIL OFL 1.1

[link-yakuhanjp-repo]: https://github.com/qrac/yakuhanjp
[link-download]: https://github.com/qrac/yakuhanjp-ex/archive/master.zip
[link-npm]: https://www.npmjs.com/package/yakuhanjp-ex
[link-jsdelivr]: https://cdn.jsdelivr.net/npm/yakuhanjp-ex/
[link-notosans]: https://www.google.com/get/noto/#sans-jpan
[link-notoserif]: https://www.google.com/get/noto/#serif-jpan
[link-roundedmplus1c]: http://jikasei.me/font/rounded-mplus/
[link-twitter]: https://twitter.com/Qrac_JP
[link-qranoko]: https://qranoko.jp
