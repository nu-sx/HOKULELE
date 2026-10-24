# Hokulele 分光解析デモ用データ

このフォルダのファイルは、Hokulele の「動画」タブにある **分光解析デモ** が
起動時にダウンロードして使います。アプリ本体には同梱していません。

| ファイル | 内容 |
|---|---|
| `manifest.json` | デモの説明、ファイル一覧 (サイズ・SHA-256)、各ステップの解析パラメータ |
| `sample_synthetic_meteor.avi` | 合成流星動画 (960x480, 60 フレーム, Na I D / Mg I b 輝線) |

取得先 URL: `https://raw.githubusercontent.com/nu-sx/hokulele/main/demo/`

## 更新するとき

動画を差し替えたら、`manifest.json` の `size` と `sha256` を必ず更新してください。
値が一致しないと、アプリはダウンロードしたファイルを破損とみなして使いません。

```
shasum -a 256 sample_synthetic_meteor.avi     # macOS
certutil -hashfile sample_synthetic_meteor.avi SHA256   # Windows
```

## パラメータ (params)

座標はすべて元動画のピクセル座標 (x, y) で、通常のクリック操作と同じ位置です。

- `frame_range`: 測光範囲 [始点, 終点]
- `gamma_index`: ガンマ設定の番号 (0 = RAW)
- `dark_range`: ダークに使うフレーム範囲
- `fov_deg`: 水平画角 [度]
- `tilt_points`: 同じ輝線の上の点 (スペクトルの傾き)
- `band_points`: 測光帯の上端と下端
- `wavecal_pairs`: 輝線同定 [ピクセル, 波長 nm]
- `zero_init`: 開始フレームでの 0 次像の位置
- `sens_mode`: 感度曲線 (`none` = 補正なし)
- `filters`: 合成測光するフィルター

## English

The files in this folder are downloaded by the **spectral analysis demo** ("Start demo" in the
Movie tab of Hokulele). They are not bundled with the app.
`manifest.json` holds the demo description (`title_en` / `description_en` for English),
the file list (size, SHA-256) and the analysis parameters of each step.
If you replace the movie, update `size` and `sha256` in `manifest.json`;
otherwise the app treats the downloaded file as corrupted.
