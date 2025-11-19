# tenvとは
Terraformのバージョンの管理ツール

## コマンド
1. `tenv tf list-remote --stable` で公式リリースを確認
2. `tenv tf install 1.6.6` で目的バージョンを取得
3. `tenv tf use 1.6.6` でデフォルトを切り替え
4. `terraform -v` などでバージョン確認
5. `tenv tf list` でインストール済みのバージョンを確認
