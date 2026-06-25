# skills

AIエージェントで利用する skill を管理するためのリポジトリです。

## Skills

- `structure-first-docs`: 技術文書を、読者が構造を復元しやすい形に生成・レビューするためのスキルです。並列・対比・因果を明示し、曖昧な前提や parse error を検出します。

## Layout

```text
skills/
  structure-first-docs/
    SKILL.md
    agents/openai.yaml
```

## Local use

このリポジトリから使う場合は、必要な skill ディレクトリを `~/.agents/skills/` にコピーします。

```bash
cp -R skills/structure-first-docs ~/.agents/skills/structure-first-docs
```
