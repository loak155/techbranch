# techbranch

技術サイト・ブログの記事を一元管理するアプリ

## 使用技術

<p>
<img src="https://img.shields.io/badge/-Go-silver.svg?logo=go">
<img src="https://img.shields.io/badge/-PostgreSQL-silver.svg?logo=postgresql">
<img src="https://img.shields.io/badge/-Redis-silver.svg?logo=redis">
<img src="https://img.shields.io/badge/-TypeScript-silver.svg?logo=typescript">
<img src="https://img.shields.io/badge/-React-silver.svg?logo=react">
<img src="https://img.shields.io/badge/-Docker-silver.svg?logo=docker">
<img src="https://img.shields.io/badge/-GitHub Actions-silver.svg?logo=githubactions">
<img src="https://img.shields.io/badge/-Terraform-silver.svg?logo=terraform">
<img src="https://img.shields.io/badge/-AWS-silver.svg?logo=amazonwebservices">
<img src="https://img.shields.io/badge/-AWS Fargate-silver.svg?logo=awsfargate">
<img src="https://img.shields.io/badge/-AWS RDS-silver.svg?logo=amazonrds">
<img src="https://img.shields.io/badge/-AWS ElastiCache-silver.svg?logo=amazonelasticache">
<img src="https://img.shields.io/badge/-AWS Route53-silver.svg?logo=amazonroute53">
<img src="https://img.shields.io/badge/-AWS SES-silver.svg?logo=awssecretsmanager">
<img src="https://img.shields.io/badge/-AWS CloudWatch-silver.svg?logo=amazoncloudwatch">
</p>

## URL

- [アプリケーション](https://app.techbranch.link/)
- [API ドキュメント](https://api.techbranch.link/docs)

## テストアカウント

ログイン画面からゲストログインを押下ください。

## 機能

- サインアップ

  - 登録後、ユーザ認証のメール送信する

  - メールでの URL リンクから認証すると本登録する

- ログイン
  - Email・パスワードでのログインする
  - Google アカウントでのログインする
- 記事一覧
  - 記事の一覧を表示する
  - 記事をクリックすると記事本文へ遷移する
- ブックマーク
  - ブックマークを登録する
  - ブックマークを削除する
  - ブックマーク一覧からブックマークした記事の一覧を表示する
- コメント
  - コメントを登録する
  - コメントを表示する

<table>
  <tr>
    <th>サインアップ</th>
    <th>メールユーザ認証</th>
  </tr>
  <tr>
    <td><img src="./docs/Signup.gif"></td>
    <td><img src="./docs/PreSignup.gif"></td>
  </tr>
  <tr>
    <th>ログイン</th>
    <th>Googleログイン</th>
  </tr>
  <tr>
    <td><img src="./docs/Login.gif"></td>
    <td><img src="./docs/GoogleLogin.gif"></td>
  </tr>
  <tr>
    <th>ゲストログイン</th>
    <th>ログアウント</th>
  </tr>
  <tr>
    <td><img src="./docs/GuestLogin.gif"></td>
    <td><img src="./docs/Logout.gif"></td>
  </tr>
  <tr>
    <th>記事一覧</th>
    <th>ブックマーク</th>
  </tr>
  <tr>
    <td><img src="./docs/Article.gif"></td>
    <td><img src="./docs/Bookmark.gif"></td>
  </tr>
  <tr>
    <th>コメント</th>
  </tr>
  <tr>
    <td><img src="./docs/Comment.gif"></td>
  </tr>
</table>

## AWS 構成図

<img src="https://github.com/loak155/techbranch-infra/raw/main/docs/architecture-diagram.png">

## ER 図

<img src="https://github.com/loak155/techbranch-backend/raw/main/docs/db/Entity-Relationship-Diagram.png">