# Skill: prompt-session

## Purpose
ネームをNano Banana Pro向け生成プロンプトに変換する。

## Mandatory Rules
- `ASPECT RATIO: 3:4 portrait orientation`
- 参照画像指定を先頭に記載
- キャラ仕様（翔一/クロちゃん）を省略しない
- 話者名ラベルを書かない
- 禁止モード（天啓/布団）を違反しない

## Workflow
1. 7要素順序で記述。
2. 画風指定を最後に統合。
3. 文字化け回避のため日本語長文を抑制。
4. 変更点を1〜2点に限定して反復。

## Output Format
- 画像生成用全文プロンプト
- 後付けセリフ表（コマ別）
- 改善提案（最大3件）
