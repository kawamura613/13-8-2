概要
COACHTECH　教材　Tutorial　13-8-3: 認証機能のテストの実施で作成した成果物です。
ログイン機能のテスト、ユーザー登録機能のテスト、未認証ユーザーのリダイレクトテスト
を行いました。

使用技術
PHP 8.X
Laravel 10.x

学んだこと
正常系（認証成功）・異常系（認証失敗）を中心に考えることを学びました。


動作確認
sail test tests/Feature/AuthenticationTest.phpで特定ユーザーとして認証されていることを確認
sail test tests/Feature/RegistrationTest.phpでユーザー登録テストを確認
sail test tests/Feature/UnauthenticatedRedirectTest.phpでに承認時の確認を行う
