# terminalnight2-secure-ssh-key-management-guide

2026/03/27に開催された[Terminal Night #2](https://kichijojipm.connpass.com/event/382650/)の発表資料です。
ターミナルで動作するプレゼンツール[presenterm](https://github.com/mfontanini/presenterm)を使っています。

ターミナルは[Kitty](https://github.com/kovidgoyal/kitty)推奨です。

```sh
brew install presenterm
presenterm main.md
```

PDFの出力例は以下の通り。必要に応じて `presenterm.conf` 内のフォントパスを書き換えてください

```sh
brew install font-udev-gothic-nf weasyprint
presenterm -c presenterm.conf -e main.md
```
