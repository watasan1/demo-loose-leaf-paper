# demo-loose-leaf-paper

## git

### gitignore

```bash
echo .DS_Store >> .gitignore
```

### commit message

Prefixをつける。Prefixとは接頭辞のことで、何かしらのテキストの先頭に文字をつける文化のことです。

ルールは色々ありますが。

feat: 新しい機能
fix: バグの修正
docs: ドキュメントのみの変更
style: 空白、フォーマット、セミコロン追加など
refactor: 仕様に影響がないコード改善(リファクタ)
perf: パフォーマンス向上関連
test: テスト関連
chore: ビルド、補助ツール、ライブラリ関連

を利用します。

理由を簡潔に続けます。

feat: 〇〇なため、△△を追加

変更した理由や目的を書くことでコードレビューが圧倒的にしやすくなります。

