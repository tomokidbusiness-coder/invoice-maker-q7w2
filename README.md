# 請求書メーカー

ブラウザで請求書を作って、PDFで保存できるツールです。

- 入力した内容は、このブラウザの中だけで処理されます。外部には送信されません。
- 入力は、この端末のブラウザに自動で保存されます(別の端末とは共有されません)。
- 消費税は税率ごとにまとめて1回計算します(10%・8%・非課税)。端数処理は選べます。
- 「PDFをダウンロード」または「印刷 / きれいなPDFで保存」でPDFにできます。

## 使っている部品
- [html2canvas](https://html2canvas.hertzen.com/) 1.4.1 (MIT License)
- [html2pdf.js](https://github.com/eKoopmans/html2pdf.js) 0.10.1 (MIT License)
