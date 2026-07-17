# リポジトリ作成手順

## リポジトリ作成

Repositories>New Repository

- Repository Nameは命名ルールあり（PJ番号頭3文字-年度2ケタ-任意のPJ名-内容）

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
