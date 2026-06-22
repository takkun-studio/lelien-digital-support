# Codex 作業場所選択ルール

Codex作業では、GitHubリポジトリ作業とMacローカル作業の入り口を逆に扱わない。

## 結論

```text
GitHubリポジトリを触る作業
→ 対象リポジトリを選ぶ
→ ai-work-rules / lelien-digital-support などを指定する
→ PR作成・md更新・README修正・リポジトリ内整理向き

Macローカルのファイルを触る作業
→ 余計なリポジトリやプロジェクトを選ばない
→ 何も選ばず、指示で対象パスを指定する方が通りやすい場合がある
→ Downloads / iCloud Drive / AI作業倉庫 などFinder上の実ファイル整理向き
```

## GitHub作業

GitHub作業では、対象リポジトリを選ぶ。

例：

```text
ai-work-rules
lelien-digital-support
kdp-image-generator
```

用途：

- ルールmd更新
- README修正
- AGENTS.md追記
- PR作成
- リポジトリ内ファイル整理

この場合、MacのDownloadsやiCloud Driveを作業場所として開く必要はない。

## Macローカル作業

Mac内のファイルを触る場合は、GitHubリポジトリを選ばない。

DownloadsやiCloud Driveの整理は、リポジトリ作業ではなくFinder上の実ファイル操作。

対象は指示内で明示する。

例：

```text
~/Downloads
iCloud Drive/Downloads
iCloud Drive/AI作業倉庫
```

用途：

- Downloads整理
- iCloud Driveへの移動
- ローカルファイルの再振り分け
- Finder上の実ファイル操作

## 禁止

- GitHub作業なのに、ローカルDownloadsやiCloud Drive整理として扱わない
- ローカル整理なのに、GitHubリポジトリを選ばせない
- GitHubリポジトリ選択とMacローカル作業場所選択を混同しない
- Codexクラウド、Codexアプリ、ターミナルCLIを混同しない
- `codex` コマンドが無い状態で、CLI前提の説明をしない

## 今後の判断

```text
リポジトリを直す話
→ 対象リポジトリを選ぶ
→ ai-work-rules 等を指定する

Mac上のファイルを整理する話
→ リポジトリを選ばない
→ 何も選ばず、指示でDownloads/iCloud Drive等の対象パスを指定する
```
