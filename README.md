# PDFDecrypter

![PdfUnlock](https://user-images.githubusercontent.com/92504306/202094787-661ba2b6-4729-42a8-a3f4-54314b97b6a6.png)

## 概要
このシェルスクリプトはPDFのパスワードを解除するものです。パスワード解除にはUserパスワードが必要です。パスワードが分かっていないPDFは解除できないので気を付けてください。

## 注意事項
パスワードファイルの位置や読み込むフォルダーの位置などはsettings.jsonから読み込んでいます。必ずMain.ps1と同じ階層に配置してください。

## 使い方
Runファイルをダブルクリックすると、スクリプトの実行が開始されます。
パスワードはpasswords.csvから読み込みます。対象の名前とパスワードをcsvファイルに書いてください。

## 使用したライブラリー
qpdf-10.6.3<br>
iTextSharp version-5.5.13.3