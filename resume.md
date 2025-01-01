# 職務経歴書

## バリューコマース株式会社 (2021/04 ~ 2023/07)

守秘義務のため概要のみ記載しています

- 顧客側管理画面を改修・モダンな環境にリプレイス
- 既存システムにテスト環境を構築・CIによる自動テスト環境構築
- 新規プロジェクトに主体的に参画
  - インフラ構築
  - FE設計・開発・テスト・運用
  - BE設計・運用

---
## CoeFont株式会社 (2023/08 ~ )

### webアプリケーションの改善
#### 概要
#### 担当技術スタック
#### 担当業務

WIP

### Electronを使ったデスクトップアプリ開発プロジェクト
#### 概要

ボイスチェンジャーのデスクトップアプリの保守・改修

#### 担当技術スタック

- デスクトップアプリ
  - TypeScript (Electron, React)
  - Python
- Backend/Infra
  - AWS (S3, Lambda, ALB, CloudFront)
  - Firebase (Authentication, RemoteConfig)
  - Go (echo)
  - GitHub Actions

#### 担当業務

- デスクトップアプリ
  - UIの実装
  - Auto updaterの実装
  - macOS, Windowsのcode signing
  - Pythonを使った音声変換処理の実装
  - アプリサイズの削減
- Backend/Infra
  - デスクトップアプリのAuto updaterのためのS3/CloudFront構築
  - GitHub Actionsを使用したCI/CDの構築（lint, build, deploy）

### Tauriを使ったデスクトップアプリ開発プロジェクト
#### 概要

- 以下の機能を持ったデスクトップアプリの開発
  - ボイスチェンジャー
  - 同時翻訳
- アプリで使用するオーディオドライバーの開発

#### 担当技術スタック

- デスクトップアプリ
  - Rust (Tauri)
  - TypeScript (React)
- Backend/Infra
  - AWS (S3, Lambda, ALB, CloudFront)
  - Firebase (Authentication, RemoteConfig)
  - Go (echo)
  - GitHub Actions
- オーディオドライバー
  - C (macOS; CoreAudio)
  - C++ (Windows; WDK)

#### 担当業務

- デスクトップアプリ
  - UIの実装
  - Auto updaterの実装
  - macOS, Windowsのcode signing
  - Rustを使った音声変換処理の実装
  - audioのI/Oとしてweb socketを実装
- Backend/Infra
  - デスクトップアプリのAuto updaterのためのS3/CloudFront構築
  - GitHub Actionsを使用したCI/CDの構築（lint, build, deploy）
- オーディオドライバー
  - macOSにおける仮想オーディオデバイスの開発・署名
  - macOSにおけるオーディオデバイスのインストーラーの開発・保守
  - Windowsにおける仮想オーディオデバイスの開発・テスト・署名 (Microsoft Partner CenterでのWHQL含む)
  - Windowsにおけるオーディオデバイスのインストーラーの開発・保守

## 朝日印刷株式会社 (2019/07 ~ )

### Androidアプリ開発プロジェクト

#### 概要

- AR技術を用いたAndroidアプリの開発
- toB向けのモバイルアプリ管理システムの開発

#### 担当技術スタック

- Androidアプリ
  - Android SDK
  - Kotlin
- 管理システム
  - フロントエンド(Web): TypeScript, Nuxt.js, Vue, Vuex, Vuetify

#### 担当業務

- Androidアプリ
  - [ARCore](https://developers.google.com/ar)を用いた画像のトラッキング、3D・音声・動画・画像データの表示を実装
  - 写真機能の実装
  - [Android アプリリンク](https://developer.android.com/training/app-links)実装
  - アプリのリリース作業担当
  - アプリに実装する機能の提案・企画・実装
- 管理システム
  - モバイルアプリに表示するデータを管理するための管理ページをwebで作成
  - 音声・動画・3Dモデルのプレビュー実装
  - 閲覧回数などの統計情報をグラフで表示

### ECサイト開発プロジェクト

#### 概要

- インターネット印刷サービスの開発

#### 担当技術スタック

- フロントエンド(Web): TypeScript, Nuxt.js, Vue, Vuex, Vuetify
- フロントエンド(iOS): Swift, UIKit, SwiftUI
- バックエンド: Go, Echo
- インフラ: GCP, Firebase
- データベース: Firestore Database
- CI/CD, XaaS: GitHub Actions, GAS, PayJP

#### 担当業務

- FE（顧客が閲覧するECサイト）画面
  - ログイン機能実装
  - テーブル型の料金表UI実装
  - 決済システムをPayJPにて実装
  - カートシステムの実装
  - マイページ機能実装
- BE・インフラ・DB設計・開発
  - 印刷サービス注文システムの設計・実装
  - PayJPを用いた決済システムの設計・実装
  - BFFとしてFEへデータを返すAPIの設計・実装
- ECサイトの管理画面
  - Catalystを用いたmacOSで動くアプリケーション開発
  - `NavigationView` を使用したナビゲーションUI実装
  - `UICollectionView` を使用したExcel風のテーブルUI実装
  - Firestore DatabaseへのCRUD

## windhole株式会社 (2022/02 ~ 2023/01)

### モバイルアプリケーション開発

#### 概要

- モバイルアプリケーション (クラスプラットフォーム; iOS / Android) の新規開発・運用
- FEのコードオーナー

#### 技術スタック

- フロントエンド（Mobile）: Dart, Flutter
- バックエンド: Go
- インフラ: GCP, Firebase
- データベース: MySQL
- CI/CD, XaaS: GitHub Actions

#### 担当業務

- FEのコードオーナーを担当
  - コーディング規約・アーキテクチャなどコードの品質を保つために最終的な決定を下す
  - Clean Architectureに沿った開発の促進
  - テスト開発駆動の促進
  - パッケージのバージョン管理
- モバイルアプリケーション開発
  - Flutterを用いてiOS, Androidのモバイルアプリを１から開発
  - タイトな開発スケジュールに合わせた機能の取捨選択
  - アプリの主要機能の実装
  - チャット機能実装
  - フリックでアクションが選択可能なUIの実装
  - 無限スクロールページャーの実装
  - pull to refreshの実装
  - タイムライン機能実装
  - 運用フェーズにおけるDBの仕様変更に対して、ユーザに不都合が生じないようなAPIを設計
