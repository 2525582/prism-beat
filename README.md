# PRISM//BEAT // LIVE STAGE

単一HTMLファイル（index.html）で完全ローカル完結動作するオリジナル4レーンリズムゲーム。

- 外部通信・CDN不使用 / iPad Safari オフライン対応
- 描画基準は AudioContext.currentTime に直結（音ズレゼロ同期エンジン）
- 初期キャラクターはオーナー承認済みのノエル1名のみ（UNIT_CHARACTERS）
- 楽曲差し替え: SONG_LIST の audioUrl に MP3 パスを指定
- 背景差し替え: STAGE_CONFIG の backgroundImage / backgroundVideo にパスを指定、またはゲーム内 STAGE 画面でローカルファイル選択
- 立ち絵差し替え: UNIT_CHARACTERS の imageUrl に PNG パスを指定
- クリエイタースタジオ: 16ステップシーケンサー + 譜面配置 + 即テストプレイ + 書き出し
- キャラ追加はゲーム内「キャラ追加申請フォーム」から申請書を生成し、オーナー承認を得る形式

公開: GitHub Pages (main / root)
