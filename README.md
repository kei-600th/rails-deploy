# はじめに
こちらは製作者がAWSを用いたインフラ構築の学習のために作成したRailsアプリケーションです。
アプリケーションの内容は「Railsチュートリアル」を踏襲したものとなっております。
# インフラ設計図
<img width="834" alt="インフラ設計図" src="https://user-images.githubusercontent.com/72121574/154018770-0f71ee43-0bf7-47dd-8fde-c4cd16c2e25f.png">

# インフラ構築の内容
・EC2を用いてクラウド上にWebアプリケーションの動作環境を構築  
・ユーザーはEC2のパブリックIPアドレスにアクセスすることで利用可能  
・ユーザーによって投稿された画像ファイルはAWSのS3に保存  
・一部の機能はHerokuという外部のクラウドサービスと連携させることによって実装  
・Githubアクションによって自動テスト,自動デプロイの実現  

# アプリケーションのURL
http://35.74.39.178/