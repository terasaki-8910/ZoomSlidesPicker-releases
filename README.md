# ZoomSlidesPicker（配布用）

授業の画面（Zoom のライブ、SharePoint の動画の再生など）から、スライドが切り替わるたびにその画像を自動で保存し、授業の後にスライド一式（PNG と PDF）を残す常駐アプリの、インストーラーと更新ファイルの置き場所です。ソースコードはここにはありません。

## 入手

[最新のリリース](https://github.com/terasaki-8910/ZoomSlidesPicker-releases/releases/latest) から:

- Mac（Apple シリコン）：`ZoomSlidesPicker_<版>_aarch64.dmg`。署名は自己署名です。「開発元を確認できない」などで開けないときは、`xattr -cr /Applications/ZoomSlidesPicker.app` を実行してから開きます。
- Windows（x64）：`ZoomSlidesPicker_<版>_x64-setup.exe`。署名していないので、「Windows によって PC が保護されました」と出たら「詳細情報」→「実行」。

## 更新

0.1.7 からは、アプリが起動するたびにここの `latest.json` で新しい版を確かめ、その場で更新できます（設定の「アップデートを確認」でも確かめられます）。更新ファイルには署名があり、署名の合わないファイルは入りません。
