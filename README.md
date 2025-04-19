# My ToDo App

## 📖 概要
Lavable（lovable.dev）と Supabase を使って作成したシンプルな ToDo アプリです。  
- メール/パスワード認証  
- メインタスク → サブタスク の階層管理  
- 完了タスクはリストの下に並べ替え  
- 未完了メインタスク数のリアルタイムカウンター  
- Supabase の RLS（Row Level Security）でユーザーごとにデータを隔離  

## 🚀 主な機能
1. ユーザー認証（サインアップ／ログイン／ログアウト）  
2. ToDo CRUD（追加・編集・完了切替・削除）  
3. サブタスク CRUD  
4. 未完了タスク数のヘッダー表示  
5. リアルタイム同期  

## ⚙️ 環境構築

### 1. Supabase の準備  
1. [Supabase](https://supabase.com) でプロジェクト作成  
2. `.env.local`（または Lovable の環境変数）に以下を設定  
   ```bash
   SUPABASE_URL=https://<your-project>.supabase.co
   SUPABASE_ANON_KEY=<your-anon-key>
