# ランディングページサンプル集

Vibeコーディング講座用のランディングページサンプル集です。

## 🚀 Vercelでのデプロイ方法

### 方法1: Vercel CLI を使用

1. **Vercel CLI をインストール**
```bash
npm i -g vercel
```

2. **プロジェクトディレクトリに移動**
```bash
cd /Users/kon39000/Desktop/VibeCode/20250703_sitetempre
```

3. **Vercelにログイン**
```bash
vercel login
```

4. **デプロイ実行**
```bash
vercel --prod
```

### 方法2: GitHub連携（推奨）

1. **GitHubリポジトリを作成**
2. **ファイルをリポジトリにプッシュ**
```bash
git init
git add .
git commit -m "Add landing page samples"
git remote add origin [YOUR_GITHUB_REPO_URL]
git push -u origin main
```

3. **Vercelダッシュボードで**
   - https://vercel.com にアクセス
   - "New Project" をクリック
   - GitHubリポジトリを選択
   - 自動でデプロイされます

## 📁 ファイル構成

```
20250703_sitetempre/
├── index.html                     # サンプル一覧ページ
├── vercel.json                     # Vercel設定ファイル
├── 01_webwriter/
│   └── index.html                  # 副業Webライター
├── 02_freelance_designer/
│   └── index.html                  # フリーランスデザイナー
├── 03_online_instructor/
│   └── index.html                  # オンライン講師
├── 04_cleaning_service/
│   └── index.html                  # 清掃サービス
├── 05_personal_brand_consultant/
│   └── index.html                  # 個人ブランドコンサルタント
├── 06_handmade_artist/
│   └── index.html                  # ハンドメイド作家
├── 07_corporate_training/
│   └── index.html                  # 企業向け研修
├── 08_company_event/
│   └── index.html                  # 会社イベント告知
├── 09_local_shop/
│   └── index.html                  # 小規模店舗（パン屋）
└── 10_startup_service/
    └── index.html                  # スタートアップサービス
```

## 🌐 アクセスURL（デプロイ後）

- **トップページ**: `https://your-project.vercel.app/`
- **各ページ**: `https://your-project.vercel.app/[ページ名]/`

例：
- 副業Webライター: `/01_webwriter/`
- デザイナー: `/02_freelance_designer/`
- オンライン講師: `/03_online_instructor/`
- など...

## 💡 特徴

- **完全レスポンシブ対応**
- **各業種に特化したデザイン**
- **30分講座での説明に最適化**
- **実際に使える実用的な構成**
- **モダンなCSS技術を使用**

## 🎯 対象者

1. **副業を始めたい人**
2. **フリーランス・個人事業主**
3. **小規模事業者**
4. **企業の担当者**
5. **スタートアップ起業家**

各ページは実際のビジネスシーンで使用できるクオリティで作成されています。