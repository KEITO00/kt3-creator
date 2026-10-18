# KT3 Creator

[English](#english) | [日本語](#日本語)

## English

App for making `.kt3` / `.kt4` files for [KT3 Player](https://github.com/KEITO00/kt3-player) (Windows).

### Features

- Opens audio, video, `.kt3` and `.kt4` files (drag and drop works)
- Loop points: set by hand, fine adjustment, automatic search, and fitting the end to the start
- Lyrics, up to two lines, with timing tools. Imports LRC and text
- BPM detection, beat grid, meter changes, chorus sections, spark cue times
- Vocal and instrumental tracks
- Thumbnail
- Trimming of audio and video
- Editing: cut, copy, paste, delete, fades, volume, and joining other audio or video
- Video preview
- Exported files can be opened and edited again
- Work in progress can be saved as a `.ktp` file, which contains all the media
  - Double-click it to continue in KT3 Creator

Output: audio is [KTC](https://github.com/KEITO00/ktc) for both `.kt3` and `.kt4`. The video of `.kt4` is MP4 with VP9 video.
See [kt3-format](https://github.com/KEITO00/kt3-format) for details.

### Supported input formats

| Type | Extensions |
|---|---|
| Audio | mp3, ogg, opus, wav, m4a |
| Video | mp4, webm, mov, mkv, avi, m4v |
| KT files | kt3, kt4 |
| Work in progress | ktp |
| Lyrics | lrc, txt |
| Thumbnail | png, jpg, webp, gif, bmp |

### Download

Download `KT3 Creator_x.x.x_x64-setup.exe` from
[Releases](https://github.com/KEITO00/kt3-creator/releases) and run it.

- Windows 10 / 11 (64-bit)
- The app checks for new versions on startup

If Windows shows "Windows protected your PC", select "More info" and then "Run anyway".

### Files you make

Files you make are yours. You are responsible for the rights to the audio, video, images
and lyrics you put in them.

### License

See [LICENSE](LICENSE). Licenses of third-party components are listed under "License"
at the bottom left of the app.

## 日本語

[KT3 Player](https://github.com/KEITO00/kt3-player) で再生する `.kt3` / `.kt4` を作成する、Windows 用のアプリケーションです。

### 機能

- 音声・動画・`.kt3`・`.kt4` の読み込み（ドラッグ＆ドロップにも対応）
- ループ位置：手動での設定、微調整、候補の自動検索、開始位置に合わせた終了位置の調整
- 歌詞（2 行まで）。タイミングの調整機能付き。LRC とテキストの読み込みに対応
- BPM の検出、拍の位置、拍子の変化、サビの区間、火花のタイミング
- ボーカルとインストの音声
- サムネイル
- 音声・動画のトリミング
- 編集：切り取り・コピー・貼り付け・削除、フェード、音量、別の音声や動画の結合
- 動画のプレビュー
- 書き出したファイルの再編集
- 編集中の状態を、素材を含めて `.ktp` ファイルに保存
  - ダブルクリックすると KT3 Creator が起動し、続きから編集できます

出力形式：音声は、`.kt3`・`.kt4` ともに [KTC](https://github.com/KEITO00/ktc) です。`.kt4` の動画は MP4（映像は VP9）です。
詳しくは [kt3-format](https://github.com/KEITO00/kt3-format) を参照してください。

### 対応する入力形式

| 種類 | 拡張子 |
|---|---|
| 音声 | mp3、ogg、opus、wav、m4a |
| 動画 | mp4、webm、mov、mkv、avi、m4v |
| KT ファイル | kt3、kt4 |
| 編集中のファイル | ktp |
| 歌詞 | lrc、txt |
| サムネイル | png、jpg、webp、gif、bmp |

### ダウンロード

[Releases](https://github.com/KEITO00/kt3-creator/releases) から
`KT3 Creator_x.x.x_x64-setup.exe` をダウンロードして実行してください。

- Windows 10 / 11（64bit）
- 起動時に新しいバージョンを確認します

「Windows によって PC が保護されました」と表示された場合は、「詳細情報」→「実行」を選択してください。

### 作成したファイルの権利

作成したファイルの権利は、作成者に帰属します。ファイルに含める音声・映像・画像・歌詞の権利は、作成者自身で確認してください。

### ライセンス

[LICENSE](LICENSE) を参照してください。第三者コンポーネントのライセンスは、アプリケーションの左下の「License」から確認できます。
