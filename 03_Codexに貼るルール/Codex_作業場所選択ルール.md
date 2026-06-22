# Codex 作業場所選択ルール

Codex作業では、クラウド作業・GitHub作業・Macローカル作業を混同しない。

## 結論

```text
GitHubリポジトリを触る作業
→ 作業場所は選ばない
→ Codex上で対象リポジトリを選ぶ
→ PR作成・md更新・README修正・リポジトリ整理向き

Macローカルのファイルを触る作業
→ 作業場所を対象フォルダにする
→ Downloads / iCloud Drive / 任意フォルダなどを開く
→ Finder上の実ファイル整理・移動・コピー向き
```

## GitHub作業

GitHub作業では、ローカルフォルダを開く必要はない。

対象リポジトリを選ぶ。

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

## Macローカル作業

Mac内のファイルを触る場合は、作業場所として対象フォルダを開く。

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

- GitHub作業なのに、無理にローカル作業場所を開かせない
- ローカル整理なのに、GitHubリポジトリを選ばせない
- Codexクラウド、Codexアプリ、ターミナルCLIを混同しない
- `codex` コマンドが無い状態で、CLI前提の説明をしない

## 今後の判断

```text
リポジトリを直す話
→ リポジトリ選択
→ 作業場所なしで進める

Mac上のファイルを整理する話
→ 対象フォルダを作業場所に選ぶ
→ DownloadsやiCloud Driveを開く
```
