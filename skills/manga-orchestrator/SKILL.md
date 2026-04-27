# Skill: manga-orchestrator

## Purpose
漫画制作全体の司令塔。リサーチ・構成・プロンプトの接続を管理する。

## Inputs
- handover / bible
- 現在の制作ステータス
- ユーザーの今回の優先タスク

## Workflow
1. 非交渉ルールを先に固定。
2. 今回スコープ（ページ単位）を定義。
3. 依存順で実行（Research -> Composition -> Prompt）。
4. 1〜2変更で反復。
5. チェックリストで品質ゲート。

## Output
- 優先順位つき作業計画
- 実行可能な次アクション
- 更新対象ファイル一覧
