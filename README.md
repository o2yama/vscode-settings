# VSCode(Cursor) 好みの設定

## ショートカット

### File: Reveal Active File in Explorer View

Explorerで開いているファイルにフォーカスを当てる

### File: Copy Relative Path of Active File

開いているファイルの相対パスを取得

## 設定

### Explorer: Auto Reveal (チェックを外す)

エディタでファイルにフォーカスが当たると、Explorerでも当たる設定（デフォルトで当たるようになっている）

## GitLens(settings.json)

```json
  "gitlens.currentLine.format": "",
  "gitlens.hovers.currentLine.changes": false,
  "gitlens.currentLine.dateFormat": "",
  "gitlens.codeLens.authors.enabled": false,
  "gitlens.blame.highlight.enabled": false,
  "gitlens.currentLine.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.dateFormat": "YYYY/MM/DD",
  "gitlens.defaultDateFormat": "YYYY/MM/DD HH:mm:ss",
  "gitlens.defaultTimeFormat": "HH:mm:ss",
  "gitlens.views.formats.commits.description": "${author, }${date}",
  "gitlens.statusBar.format": "${author}, ${date}${' via 'pullRequest}",
  "gitlens.views.formats.stashes.description": "${stashOnRef, }${date}"
```
