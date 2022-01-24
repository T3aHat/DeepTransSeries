---
title: DeepLopener series
class: DeepLopener series
repository_url: https://github.com/T3aHat/DeepLopenerSeries/projects
---

【EN】  

## Chrome extension: [DeepLopener](https://deeplopener.ml/DeepLopener)  
- [GitHub](https://github.com/T3aHat/DeepLopener)
- Page translation, translation display on PDF, document translation function, etc. are implemented.
- Featured in [GIZMODE](https://www.gizmodo.jp/2021/02/deeplopener-pro.html), [Gigazine](https://gigazine.net/news/20211231-deepl-opener/), etc. 

## Android App: [DeepLopener for Android](https://deeplopener.ml/DeepLopener_for_Android)  
- A simple Android app that just displays the translation results.
- Like Google Translate, it displays the translation results over the current opening app, so there are fewer transitions between apps, making it easier to use.

## Windows: [DeepLopenerOCR](https://github.com/T3aHat/DeepLopenerOCR)  
- Originally I implemented this app because I was dissatisfied with the fact that I couldn't use it in desktop apps even after acquiring DeepL API Pro.
    - Can be translated by using shortcuts such as Ctrl+C×2 as in the original application that is published by [deepl.com](https://deepl.com).
- OCR function by Tesseract was implemented later.
    - Monitors the clipboard data and starts automatically when the data type becomes `image`.
    - By combining with Chrome extension, the window will appear on the front page when it fires even if it is minimized.

<br>
<br>
<br>

【日本語】  

## Chrome拡張機能: [DeepLopener](https://deeplopener.ml/DeepLopener)  
- [GitHub](https://github.com/T3aHat/DeepLopener)
- ページ翻訳，PDF上に翻訳表示，ドキュメント翻訳機能等を実装
- [GIZMODE](https://www.gizmodo.jp/2021/02/deeplopener-pro.html)，[Gigazine](https://gigazine.net/news/20211231-deepl-opener/)などで取り上げられた

## Androidアプリ: [DeepLopener for Android](https://deeplopener.ml/DeepLopener_for_Android)  
- 翻訳結果を表示するだけの単純なAndroidアプリ
- Google Translateのように開いているアプリ上に翻訳結果を表示するのでアプリ間遷移が少なく使い勝手が良い

## Windows: [DeepLopenerOCR](https://github.com/T3aHat/DeepLopenerOCR)  
- 元々DeepL API Proを取得してもデスクトップアプリでは使えないことに不満を感じて実装
    - 謹製アプリ同様Ctrl+C×2などのショートカットで翻訳可能
- 後にTesseractによるOCR機能を実装
    - クリップボードのデータを監視し，imageデータになったときに自動起動
    - Chrome拡張機能と組み合わせることで最小化していても発火時に最前面に出てくる