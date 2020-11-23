## 🧑🏻‍🔧 Buiding now...

## 🏌️ Goal

- Download フォルダに保存されるファイルを自動で整理整頓する
  - 拡張子毎に専用のフォルダに移動
  - 拡張子毎にファイル名を編集
    - ex: test.text -> 2020_11_23_test.txt

## 👀 Details

- ファイル毎の移動先
  - text, pdf → Documents
  - png, jpeg, svg → Pictures
  - other... → Unsorted

**クラス**

- Obsever
  - 監視プログラム(fssm)の実行
- Organizer
  - 拡張子毎にフォルダに振り分け
- organizable
  - 拡張子毎に保存先フォルダを返却
    - 拡張子を抜き取る
    - 拡張子毎にファイルに対応するフォルダを選択

## 🛠 Tools

- Fssm ([ttilley/fssm](https://github.com/ttilley/fssm))
