
# Nextjsフルスタックテンプレート

#### 技術スタック
- Nextjs
- Typescript
- Clerk
- Supbase
- Prisma

  
### 初期設定

##### Nextjs
``` npm i ```

##### Supabase
プロジェクトの作成とDataBaseUrlの取得（session modeのurl）
＊プロジェクト作成時のデータベースパスワードは記号を使うとマイグレーションが出来なくなるので、注意

##### Prima
Prismaの初期化
``` npx prisma init ```
.envファイルにSupabaseのurlを記述する
後は、テーブルを定義して、マイグレートする。

##### Clerk
プロジェクトのルートディレクトリに.env.localを作成
``` NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_b25lLWRvcnktMTEuY2xlcmsuYWNjb3VudHMuZGV2JA```
``` CLERK_SECRET_KEY=sk_test_NkKHnBz8nSnQzWz5g1DcOZPZuxLddD6eHUyUp3ZJea ```
