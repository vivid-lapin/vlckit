---
description: vlckitを開発する際のルール
---

- 本 vlckit は vlckit に日本のARIB規格向けの対応を追加するためのフォークです
- `libvlc/vlc` に使用する vlc が入っているので、必要に応じて参照・変更を行ってください
- `libvlc/vlc` に対する変更は `libvlc/patches` にパッチとして管理します
- `libvlc/vlc` は `libvlc/patches` のパッチを適用された状態になっています
- `libvlc/vlc` の直下には一部 contrib の git フォルダが入っています。参照用として配置しているため、コミットしないでください
- `libvlc/patches` に配置するパッチは `libvlc/vlc` のコミットの format-patch から作成してください
- `libvlc/vlc` で作業する際は、vlckit ディレクトリのブランチ名に合わせてブランチを切り替えてください
  - ブランチの作成時は master を下に作成してください
- ローカルでのフルビルドは行わないでください
