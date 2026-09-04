# LazyDiary

紙の手帳（GoodNotes）に手書きした日記を、そのまま文字に起こして読める形にしたもの。

**合言葉で保護しています。** 各ページは AES-GCM で暗号化した状態でここに置いてあり、
ブラウザで合言葉を入れたときだけ手元で復号されます。合言葉はリポジトリにもサイトにも入っていません。

生成元のツールは Obsidian vault 側 `04_Random/tools/goodnotes-diary/` にあります
（`build_site.py --password ...`）。
