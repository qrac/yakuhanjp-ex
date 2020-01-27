# Yaku Han JP - EX

## About

"Yaku Han JP EX"は、"[Yaku Han JP][link-yakuhanjp-repo]"の実験的なバージョンです。

## Install

```
npm install yakuhanjp-ex
```

## YakuHanJP-EX-Science

![YakuHanJP-EX-Science IMAGE](https://i.gyazo.com/314f88eb025d2a9ced9103ac75014332.png)

YakuHanJP に理工系文章のカンマ `，` とピリオド `．` を加えたバージョンです（ゴシック体のみ）。

```
// YakuHanJP-EX-Science
，．、。！？〈〉《》「」『』【】〔〕・（）：；［］｛｝
```

※バグ回避のため、`.notdef` `space` `ellipsis` が含まれています

- font-weight: 100; // Thin
- font-weight: 200; // Light
- font-weight: 300; // DemiLight
- font-weight: 400; // Regular
- font-weight: 500; // Medium
- font-weight: 700; // Bold
- font-weight: 900; // Black

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/yakuhanjp-ex@0.3.0/dist/css/yakuhanjp-ex-science.min.css"
/>
```

```css
.yakuhanjp {
  font-family: YakuHanJP, "Hiragino Sans", Meiryo, "Yu Gothic Medium",
    sans-serif;
}
```

## YakuHanJP-EX-Emotion

![YakuHanJP-EX-Emotion IMAGE](https://i.gyazo.com/a6c553458628caab5ed2c6ccf79812ed.png)

YakuHanJP から感嘆符・疑問符を抜いたもの（ゴシック体のみ）。Emotion とは無感情の意を表しています。

```
、。〈〉《》「」『』【】〔〕・（）：；［］｛｝
```

※バグ回避のため、`.notdef` `space` `ellipsis` が含まれています

- font-weight: 100; // Thin
- font-weight: 200; // Light
- font-weight: 300; // DemiLight
- font-weight: 400; // Regular
- font-weight: 500; // Medium
- font-weight: 700; // Bold
- font-weight: 900; // Black

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/yakuhanjp-ex@0.1.1/dist/css/yakuhanjp-ex-emotion.min.css"
/>
```

```css
.yakuhanjp-ex-emotion {
  font-family: YakuHanJP-EX-Emotion, "Hiragino Sans", Meiryo,
    "Yu Gothic Medium", sans-serif;
}
```

## ~~YakuHanJP-EX-CDN-SCSS~~

~~SCSS ファイルで CDN フォントファイルを呼び出すバージョンです。`npm install` してプロジェクトの SCSS ファイルから各 SCSS ファイルをインポートします。~~

SCSS ファイル での CDN 読み込みは、[本家 Yaku Han JP][link-yakuhanjp-repo] で対応しました。そちらをお使いください。

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
