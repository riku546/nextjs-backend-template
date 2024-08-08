
# Nextjsフルスタックテンプレート

#### 技術スタック
- Nextjs
- Typescript
- Clerk
- Supbase
- Prisma

  
## 初期設定

### Nextjs
    
    npm i 

### Supabase
プロジェクトの作成とDataBaseUrlの取得（session modeのurl）
＊プロジェクト作成時のデータベースパスワードは記号を使うとマイグレーションが出来なくなるので、注意

### Prima
Prismaの初期化

    npx prisma init 

.envファイルにSupabaseのurlを記述する
後は、テーブルを定義して、マイグレートする。

### Clerk
公式ドキュメントを参照。
https://clerk.com/docs/quickstarts/nextjs
