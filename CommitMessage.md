# Prefix

- fix：バグ修正
- add：新規（ファイル）機能追加
- update：機能修正（バグではない）
- clean：整理（リファクタリング等）
- remove：削除（ファイル）
- wip：作業中

# Format

- 1 行目  
  [prefix]コミット要約
- 2 行目  
  空行
- 3 行目以降  
  コミットで対応した内容、やり残した作業

# Example

    [clean]ツイート送信の際の取得元を state に変更

    修正はできたが、ツイート送信後にテキストエリアを空にする処理が完成していない。
    また、ツイート編集時の処理も取得元を state に変更する必要がある。

# 参考

[Git のコミットメッセージの書き方](https://qiita.com/itosho/items/9565c6ad2ffc24c09364)
