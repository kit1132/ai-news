# デイリーチェック対象サイト

## 最優先

### Claude Code Changelog
- URL（優先）: https://code.claude.com/docs/en/changelog
- URL（フォールバック）: https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md
- 取得方法: WebFetch。GitHub版は大きいため429になることがある。公式ドキュメント版を優先
- 注目点: 新バージョンリリース、破壊的変更、新機能
- 頻度: 毎日確認

### Anthropic Blog / News
- URL: https://www.anthropic.com/news
- 代替URL: なし
- 検索キーワード（WebSearch用）: `Anthropic news announcement 2026`
- 取得方法: WebFetch → 403/429時はWebSearch（`site:anthropic.com/news 2026` → 0件なら `Anthropic news announcement 2026`）
- 注目点: 新モデル、新プロダクト、API変更、料金変更
- 頻度: 毎日確認

### Claude Release Notes（サポートサイト）
- URL: https://support.claude.com/en/articles/12138966-release-notes
- 代替URL: なし
- 検索キーワード（WebSearch用）: `Claude release notes update 2026`
- 取得方法: WebFetch → 403/429時はWebSearch（`site:support.claude.com release-notes 2026` → 0件なら `Claude release notes update 2026`）
- 注目点: Claudeプロダクト全体のリリースノート（Web/Desktop/Mobile/API含む）。Changelogとは別軸の情報源
- 頻度: 毎日確認

## 高優先

### Cursor Changelog
- URL: https://cursor.com/changelog
- 代替URL: なし
- 検索キーワード（WebSearch用）: `Cursor changelog new features 2026`
- 取得方法: WebFetch → 403/429時はWebSearch（`site:cursor.com changelog 2026` → 0件なら `Cursor changelog new features 2026`）
- 注目点: 新機能、エージェント改善、IDE統合、料金変更
- 頻度: 毎日確認

### Devin Release Notes
- URL: https://docs.devin.ai/release-notes/overview
- 代替URL: なし
- 検索キーワード（WebSearch用）: `Devin AI release notes update 2026`
- 取得方法: WebFetch → 403/429時はWebSearch（`site:docs.devin.ai release-notes 2026` → 0件なら `Devin AI release notes update 2026`）
- 注目点: 新機能、モデル更新、料金変更
- 頻度: 毎日確認

### X (トレンド検索)
- 取得方法: WebSearch（直接アクセス不可のため検索経由）
- 検索キーワード例:
  - "AI new tool release"
  - "LLM update announcement"
  - "Claude Code"
  - "AI agent launch"
  - "AIツール 新機能"
  - "coding agent release"
- 注目点: 話題のAIツール、バズっている技術トピック
- 頻度: 毎日確認

## 将来追加候補
