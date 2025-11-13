# 創新株式会社 公式ウェブサイト

## プロジェクト概要
創新株式会社（ソウシンカブシキカイシャ）のプレミアム送迎サービスを紹介する日本語単一ページウェブサイト。

## 会社情報
- **会社名**: 創新株式会社
- **読み方**: ソウシンカブシキカイシャ
- **代表取締役**: 張 勝
- **所在地**: 〒132-0035 東京都江戸川区松島1-34-13
- **電話番号**: 03-6337-2423
- **希望ドメイン**: createnew

## ウェブサイトの特徴

### 主要セクション
1. **ヘッダー** - 固定ナビゲーション、電話ボタン
2. **メインビジュアル** - グラデーション背景、CTAボタン
3. **会社概要** - サービスの強み、特徴4点
4. **サービス内容** - 6種類のサービス（空港送迎、ビジネス送迎等）
5. **車両紹介** - ハイエース、アルファードの2車種
6. **お問い合わせ** - 会社情報、問い合わせフォーム
7. **フッター** - 会社情報、サイトマップ

### デザイン
- **カラースキーム**: 青系統（#2c5aa0）を基調としたプロフェッショナルデザイン
- **フォント**: Noto Sans JP、Noto Serif JP（Google Fonts）
- **レスポンシブ**: モバイル、タブレット、デスクトップ対応

### 技術スタック
- HTML5
- CSS3（グリッドレイアウト、フレックスボックス）
- Vanilla JavaScript（スムーズスクロール、アニメーション効果）

## ファイル構成
```
website/
├── index.html       # メインHTMLファイル
├── style.css        # スタイルシート
├── script.js        # JavaScript機能
└── README.md        # このファイル
```

## ローカル開発
1. ブラウザで `index.html` を開く
2. または、簡易サーバーを起動:
   ```bash
   # Python 3の場合
   python -m http.server 8000
   
   # Node.jsの場合（http-server）
   npx http-server
   ```
3. ブラウザで `http://localhost:8000` にアクセス

## カスタマイズポイント

### 車両画像の追加
`style.css` の `.fleet-placeholder` セクションを編集し、実際の車両画像を追加:
```css
.fleet-image {
    background-image: url('images/hiace.jpg');
    background-size: cover;
    background-position: center;
}
```

### 色の変更
メインカラーを変更する場合、`style.css` の以下の箇所を編集:
- `#2c5aa0` - メインブルー
- `#1e3f70` - ダークブルー（ホバー効果）
- `#4a7bb8` - ライトブルー（グラデーション）

### フォーム送信先の設定
`script.js` のフォーム送信処理を実際のバックエンドに接続:
```javascript
// 実際のAPI送信処理を実装
fetch('/api/contact', {
    method: 'POST',
    body: JSON.stringify(data),
    headers: {'Content-Type': 'application/json'}
});
```

## ブラウザ対応
- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)
- モバイルブラウザ (iOS Safari, Chrome Mobile)

## SEO対策（今後の推奨事項）
- [ ] メタタグ追加（description, keywords）
- [ ] OGP画像設定
- [ ] 構造化データ（JSON-LD）
- [ ] sitemap.xml作成
- [ ] robots.txt作成
- [ ] Google Analytics設定
- [ ] ページ速度最適化

## 連絡先
創新株式会社  
電話: 03-6337-2423  
住所: 東京都江戸川区松島1-34-13

---
© 2025 創新株式会社 All Rights Reserved.