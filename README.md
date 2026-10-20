# DougaKiritoriKun third-party sources and licenses

動画切り取りくんに同梱するFFmpeg・FFprobe・mpvの対応ソース、ビルド資料、第三者ライセンスの配布先です。
アプリ本体は無償・非OSSであり、このリポジトリには本体ソースを含めません。

Corresponding sources, build materials and original third-party notices for the bundled media tools.
The proprietary application's source is not included. Each component retains its own license.

# OSS sources and build materials / OSSの対応ソース・ビルド資料

Source release / 対応ソース配布: https://github.com/naoijponly/DougaKiritoriKun-licenses/releases/tag/sources-0.1.0-selfbuild1-r2

- [mpv-sources-0.1.0-selfbuild1-r2.zip](https://github.com/naoijponly/DougaKiritoriKun-licenses/releases/download/sources-0.1.0-selfbuild1-r2/mpv-sources-0.1.0-selfbuild1-r2.zip)
  SHA256: `047ecaae212ebbb357454810f54d35f48a199501417b1158754e630eafa9a56a`
  Size / サイズ: 76686203 bytes
- [ffmpeg-sources-N-127650-geceaa54a38-20261018-r2.zip](https://github.com/naoijponly/DougaKiritoriKun-licenses/releases/download/sources-0.1.0-selfbuild1-r2/ffmpeg-sources-N-127650-geceaa54a38-20261018-r2.zip)
  SHA256: `915683c4d89fbd1a75f54398795b58bab65926c335e99bdbde7ef18a82197354`
  Size / サイズ: 603198485 bytes

## Corresponding binaries / 対応する実行物

| File | SHA256 |
| --- | --- |
| ffmpeg.exe | `a64314e0f6c3b7803ee32918dd101ed61496f9f8966b43504f2ff130b409e2fe` |
| ffprobe.exe | `04e52180984185f5fd843ccf54a6549eea6180301fac602047d83c44cbe421be` |
| mpv.exe | `4a40f6c5aaba61d5b344c452a2e358f9f53adf3a207dac7023db23f123743af6` |

## Build notes / ビルド上の留保

Read BUILDING.md and CONTENTS.json inside each ZIP. Original archives and per-file notices are retained.
Download the two named source ZIPs above. GitHub's automatic Source code snapshots contain only this repository's documentation and are not the complete corresponding-source packages.
mpv uses fixed source inputs and the supplied build recipe. The FFmpeg package retains the original BtbN recipe; a byte-identical rebuild has not been performed. The exact host build-helper version selected by its `cargo update cc` step was not recovered. SOURCE_SELECTION.json explains selected inputs and exclusions; SOURCE_PROJECTIONS.json records omitted sample/test data and byte-exact retained source. Unmodified general compiler sources are excluded under GPLv3 section 1; tool pins and notices remain.

各ZIP内のBUILDING.mdとCONTENTS.jsonに構成と手順を記載しています。GitHubが自動生成するSource codeのZIPだけでは対応ソース一式にならないため、上記の2つのソースZIPを取得してください。FFmpegはバイト一致の再ビルド未実施で、元レシピが更新したホスト用cc補助ツールの厳密版は未回収です。旧構成の調査原本は除外し、収録理由と除外内容をSOURCE_SELECTION.jsonに記録しています。AMFの不使用サンプル一式とOpenAPVのテスト動画を除き、残したソースは原文バイト列を保持しています。未改変の一般コンパイラ本体の原本は除外し、固定入手先・チェックサム・許諾原文は残しています。

Keep each corresponding source release accessible while distributing its matching binaries.
対応する実行物を配布する間、当該版のソースと資料を継続して取得できる状態にしてください。
