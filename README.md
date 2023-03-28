# slack-bot-setup

## Slack と連携するための設定

下記 URL にアクセスする．

[https://api.slack.com/](https://api.slack.com/)

`Create an app` をクリック．

![](./img/slack-setup-01.png)

`From scratch` を選択．

![](./img/slack-setup-02.png)

「アプリ名（任意）」と「使用するワークスペース」を選択して `Create App` をクリック．

![](./img/slack-setup-03.png)

画面が変わるので，左側のメニューから `OAuth & Permissions` → `Scopes` 部分の `Bot Token Scopes` を `chat:write` に設定する．

![](./img/slack-setup-04.png)

`Install Workspace` がクリックできるようになっているのでクリックする．画面が変わったら `Allow` をクリック．

![](./img/slack-setup-05.png)

![](./img/slack-setup-06.png)

画面が変わるので `Bot User Access Token` をメモしておく．

![](./img/slack-setup-07.png)

Slack アプリ側で Bot を追加したい channel で「右上のメンバーボタン」→「Integrations」→ `Add an App` の順に進む．

![](./img/slack-setup-08.png)

作成したアプリ部分の `Add` ボタンをクリックする．

![](./img/slack-setup-09.png)

これで設定は完了．

