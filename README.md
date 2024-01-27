# serverless-express

Serverless Frameworkで開発するAWS Lambdaで動作するExpress.jsアプリケーション

## Usage

### Setup

依存関係をインストールする:
```
npm ci
```

`.env.local`にAWS SSO 認証情報を追記する:
```
AWS_SSO_PROFILE=
```

### Local development

ローカル開発環境を実行する:
```
npm run dev
```

### Deployment:

AWSにデプロイする:
```
npm run deploy
```

AWSにデプロイしたリソースを削除する:
```
npm run remove
```