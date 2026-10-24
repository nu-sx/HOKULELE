# Hokulele

流星動画分光解析ソフトウェア **Hokulele** の配布ページです。
This is the download page of **Hokulele**, a meteor spectroscopy analysis software for meteor videos.
[English](#english)

## ダウンロード

[Releases](https://github.com/nu-sx/hokulele/releases/latest) から、お使いの OS 用のファイルをダウンロードしてください。

| OS | ファイル |
|---|---|
| Windows 10 / 11 (64bit) | `Hokulele-<版>-Windows-x64-Setup.exe` (インストーラ) |
| macOS 12 以降 (Apple シリコン) | `Hokulele-<版>-macOS-arm64.dmg` |

### Windows
`Setup.exe` を実行し、画面の指示に従ってインストールします。
「Windows によって PC が保護されました」と表示された場合は、「詳細情報」→「実行」を押してください。

### macOS
dmg を開き、`Hokulele.app` を「アプリケーション」フォルダへドラッグします。
初回起動時に「開発元を確認できません」と表示された場合は、
「システム設定」→「プライバシーとセキュリティ」で「このまま開く」を押してください。

## 表示言語

日本語と英語に対応しています。初回起動時は OS の表示言語に合わせて表示され、
メニューバーの「言語 / Language」で切り替えられます (再起動後に反映)。

## 使用マニュアル

- [Hokulele_使用マニュアル.docx](docs/Hokulele_使用マニュアル.docx) (日本語、Word 形式)
- [Hokulele_Manual_en.docx](docs/Hokulele_Manual_en.docx) (English, Word)

画面を開いて「Download raw file」(↓ ボタン) でダウンロードしてください。
Releases の添付ファイル、インストーラ・dmg にも同梱しています。

## 分光解析デモ

アプリの「動画」タブにある「デモを開始」を押すと、このリポジトリの [`demo/`](demo/) にある
サンプル動画をダウンロードして、分光解析の手順を順番に実演します (インターネット接続が必要です)。

## 引用と謝辞

Hokulele を使った研究成果を発表する際は、次の論文を引用し、謝辞に Hokulele を使用したことを記載してください。

**引用**

> Abe, S., Ogawa, T., Maeda, K., & Arai, T. (2020). Sodium variation in Geminid meteoroids from (3200) Phaethon. Planetary and Space Science, 194, 105040. https://doi.org/10.1016/j.pss.2020.105040

**謝辞の例（英文）**

> This research made use of Hokulele, a meteor spectroscopy analysis software (Abe et al., 2020).

**謝辞の例（和文）**

> 本研究では流星分光解析ソフトウェア Hokulele（Abe et al., 2020）を使用した。

## ソースコード

ソースコードは公開していません。

---

## English

### Download

Download the file for your OS from [Releases](https://github.com/nu-sx/hokulele/releases/latest).

| OS | File |
|---|---|
| Windows 10 / 11 (64-bit) | `Hokulele-<version>-Windows-x64-Setup.exe` (installer) |
| macOS 12 or later (Apple silicon) | `Hokulele-<version>-macOS-arm64.dmg` |

**Windows:** run `Setup.exe` and follow the instructions.
If "Windows protected your PC" appears, click "More info" and then "Run anyway".

**macOS:** open the dmg and drag `Hokulele.app` to the Applications folder.
If macOS says the developer cannot be verified on first launch,
click "Open Anyway" in System Settings > Privacy & Security.

### Display language

Hokulele supports English and Japanese. On first launch it follows the OS display language;
switch it from the "言語 / Language" menu in the menu bar (takes effect after a restart).

### User manual

- [Hokulele_Manual_en.docx](docs/Hokulele_Manual_en.docx) (English, Word)
- [Hokulele_使用マニュアル.docx](docs/Hokulele_使用マニュアル.docx) (Japanese, Word)

Open the file and use "Download raw file" (↓ button). The manuals are also attached to each
release and included in the installer and the dmg.

### Spectral analysis demo

Click "Start demo" in the Movie tab. Hokulele downloads the sample movie in [`demo/`](demo/)
and demonstrates the analysis step by step (Internet connection required).

### Citation and acknowledgment

When you publish results obtained with Hokulele, please cite the following paper and
mention Hokulele in the acknowledgments.

> Abe, S., Ogawa, T., Maeda, K., & Arai, T. (2020). Sodium variation in Geminid meteoroids from (3200) Phaethon. Planetary and Space Science, 194, 105040. https://doi.org/10.1016/j.pss.2020.105040

Example acknowledgment:

> This research made use of Hokulele, a meteor spectroscopy analysis software (Abe et al., 2020).

### Source code

The source code is not public.
