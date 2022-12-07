# 音声ダイアリー
<img src="https://ksasazawa.github.io/js2_sasazawa_17/img/boice_daiary.png" width="600px">

# 課題２ -メモ帳アプリ-

## ①課題内容
- 音声ダイアリー with 広告ゲーム

## ②工夫した点・こだわった点
- カレンダー形式で日にちごとにメモを取れるようにした。
- テキスト入力だけでなく、音声入力でメモを取れるようにした。
- マップを埋め込んだ。
- 広告という名目で無理矢理じゃんけん課題を入れた。

## ③難しかった点・次回トライしたいこと(又は機能)
- 関数内のクリックイベントが、複数回呼び出すと前のクリックイベントも一緒に呼び出されてしまい、解決に時間がかかった。下記記事を参考に、クリックイベント前に「.off」を入れることで解決した。
https://hodalog.com/how-to-prevent-the-event-from-being-executed-twice/
- 非同期処理でまた苦戦した。ちょっとずつではあるが理解が進んだ気がする。

## ④質問・疑問・感想、シェアしたいtips等なんでも
- SpeechRecognition()を使うと音声入力ができる。
https://qiita.com/hmmrjn/items/4b77a86030ed0071f548
- SpeechSynthesisUtterance()を使うと音声出力ができる。
https://1-notes.com/javascript-speech-synthesis/
- カレンダー
https://nyanblog2222.com/programming/javascript/2749/
- クリックイベントが複数回呼び出される場合の処理
https://hodalog.com/how-to-prevent-the-event-from-being-executed-twice/
