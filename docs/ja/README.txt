USF4 TAG! — インストールと起動方法

Pre-alpha v0.1 · バージョン 0.1.0 · 日本語

始める前に

Windows 上のご自身の Steam 版 Ultra Street Fighter IV、PowerShell 5.1、.NET Framework 4.7.2 以降が必要です。Setup は対応 Steam ビルドと必要な元ファイルを確認します。テスト済み Simp が未導入の場合は取得用のネット接続が必要です。

これは一人一キャラクターの戦闘プレアルファで、42 キャラクターに対応します。チーム／タッグ対戦は別開発で、Hugo と Hakan は保留です。追加の 50% スタン軽減は現在 オフラインの通常 Ultra Training のみで有効です。

ランチャーの UI は英語のままです。下記は実際の英語ボタン名を使います。キャラクター名・技名も英語原文に合わせ、地域による名称の混同を避けています。

インストール

1. USF4 と Simp を通常終了し、ZIP 全体をフォルダーへ展開します。
2. USF4TAG-PreAlpha-0.1.0-Setup.exe を実行します。
3. 選択を求められたら SSFIV.exe がある Steam のゲームフォルダーを選びます。
4. Install Pre-Alpha を押し、Installation complete を待ちます。

Setup は Mod とテスト済み Simp を自動設定します。一致する既存コピーを再利用するか、配布元からダウンロードして検証します。取得できない場合は既存のテスト済みコピーを選ぶかキャンセルできます。別バージョンの既存 Simp は保護し、上書きしません。ダウンロードした Setup を削除してもデスクトップのショートカットは使えます。

遊び方

1. デスクトップの USF4 TAG Pre-Alpha を開き Launch USF4 を押します。
2. Training には入らず、ゲームの メインメニュー で待ちます。
3. ランチャーへ戻り Load Pre-Alpha を押します。
4. Simp で tag_pre_v0100 を選び Launch を押します。
5. Patching complete が表示されるまでランチャーを開いたままにします。
6. ゲームへ戻り 通常 Ultra Training に入ります。Omega や過去エディションではなく通常 Ultra のキャラクターを選んでください。

パッチ後に Training スタンルールが自動起動します。キャラクターの打ち上げ技を当て、上を保持すると空中追従します。通常技の空中チェーンは 弱または中で始動し、強で締めます。全 42 キャラクターの変更一覧 (ROSTER_CHANGES.md) に打ち上げ技、入力、例外を記載しています。

通常の USF4

USF4 と Simp を通常終了し、Play Normal USF4 を選ぶか、Simp を閉じた新しい Steam セッションで起動します。元ファイルとセーブデータは保持します。

更新と不具合報告

- Manage → Check for updates： 更新を選ぶと新しい公開インストーラーを取得・検証します。インストール前に USF4 と Simp を通常終了してください。
- Manage → Open logs： ローカルのエラー・操作レポートを開きます。
- Manage → Report a bug： 診断プレビューを表示してから入力済み GitHub issue を開きます。GitHub 上で確認・送信してください。生ログやファイルは自動アップロードしません。

修復と削除

USF4 と Simp を閉じ、Manage → Repair installation または Manage → Remove Pre-Alpha を使います。管理対象の更新・修復は復旧コピーを残します。無関係なファイルや変更済みファイルは保護され、利用者による対応が必要な場合があります。

同梱内容とサポート

インストーラー、説明、キャラクター変更 (ROSTER_CHANGES.md)、翻訳、CREDITS.txt、THIRD_PARTY_NOTICES.txt、LICENSE.txt、整合性確認用 SHA256SUMS.txt を含みます。インストーラーには常設ランチャー、実行コンポーネント、戦闘パッチが含まれます。ゲーム本体と Simp 実行ファイルは同梱しません。

GitHub プロジェクト (https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT) · 不具合報告 (https://github.com/SLresearch74/ULTRA-STREET-FIGHTER-4-TAG-PROJECT/issues)
