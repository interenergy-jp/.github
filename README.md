# リポジトリ作成手順

## リポジトリ作成

Repositories>New Repository

- Ownerはinterenergy-jp
- Repository nameは命名ルールあり（PJ番号頭3文字-年度2ケタ-任意のPJ名-内容）

上記入力してCrate repository

## リポジトリ設定

Settings>General

Automatically delete head branches LoadingのチェックON

Rules>Rulesets>New rulesets>New branch rulesets

- Rulesets Nameに「Protect Default」
- Enforcement StatusをActive
- Add bypass>managerにチェック
- Add target>Include default branches
- Branch rules>equire a pull request before mergingにチェック
- Required Approvalを「1」
- Dismiss stale pull request approvals when new commits are pushedにチェック
- Require conversation resolution before mergingにチェック

上記設定を入れ、Createを押す

## PJチーム作成

リポジトリの権限はチーム単位で管理するため、PJごとにチームを作成する

Teams>New team

- Team nameにRepository nameの共通部分を入力（PJ番号頭3文字-年度2ケタ-任意のPJ名）
- Descriptionは任意のPJ名（日本語）

上記を入力しCreate Team

その後Add memberで対象者を登録する

## リポジトリへのチームの割り付け

リポジトリを開いてSettings>General>Access>Collaborators and teams

-Add teamsで対象チームを選択>Writeを選択しAdd selection
