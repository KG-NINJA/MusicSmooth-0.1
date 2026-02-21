# MusicSmooth
MusicMouse Follower created by Gemini 3.1 pro

これは、Laurie Spiegel（ローリー・スピーゲル）の先駆的なアルゴリズミック・コンポジション・ソフトウェア「Music Mouse」にインスパイアされた、ブラウザ上で動作するMIDI作曲ツールです。

音楽理論の知識がなくても、キャンバス上をマウスでなぞるだけで、常に音楽的な響きを持った多声部（マルチボイス）のMIDIフレーズを生成できます。

## ✨ 特徴 (Features)

* **直感的な操作**: キャンバス上をドラッグ（またはスワイプ）するだけで作曲が可能。
* **アルゴリズミック生成**: Cメジャースケールにクオンタイズされ、X軸（メロディと3度上）とY軸（ベースと5度下）の座標から自動的に4声の和音を生成します。
* **インブラウザ再生**: 生成されたMIDIファイルをその場でプレビュー再生できます（Tone.js / Magenta Musicベース）。
* **MIDIエクスポート**: 気に入ったフレーズは `.mid` ファイルとしてダウンロードし、お好きなDAW（Ableton Live, Logic Proなど）で編集・拡張できます。
* **レスポンシブ・タッチ対応**: PCのマウス操作だけでなく、スマートフォンやタブレットのタッチ操作にも対応しています。

## 🚀 使い方 (Usage)

1. `index.html` をブラウザで開きます。
2. 画面中央の黒いキャンバス領域を、クリック＆ドラッグ（タッチパネルならスワイプ）して自由に図形や軌跡を描きます。
3. マウス（指）を離すと録音が終了し、裏側で即座にMIDIデータが生成されます。
4. 数秒待つとプレイヤーの準備が完了するので、**▶（再生）ボタン**を押してプレビューを聴きます。
5. 気に入ったら**「生成したMIDIをダウンロード」**ボタンを押して保存します。

## 🛠 使用技術 (Technologies Used)

* HTML5 Canvas API (軌跡の描画)
* [midi-writer-js](https://github.com/grimmdude/MidiWriterJS) (MIDIファイルの生成)
* [Tone.js](https://tonejs.github.io/) & [Magenta Music / html-midi-player](https://github.com/magenta/html-midi-player) (ブラウザ内でのMIDIプレビュー再生)

## 📄 ライセンス (License)

このプロジェクトは [MIT License](LICENSE) のもとで公開されています。自由に改変や再配布が可能です。
