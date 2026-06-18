#API 仕様

## POST /api/oo
説明：新規アカウント登録
リクエスト：{"email": "example@gmail.com", "password": "secure password123", "display.name": "クローセット太郎"}

レスポンス：{"status": "success", "message: "アカウントが正常に作成されました", "data": "user.id": "u-987654321", "email": "example@gmail.com", "display-name": "クローゼット太郎", "created.at": "2026-05-12T15:50:002"}

## POST /api/oo
説明：新しい服の登録
レスポンス：{"id": "i01", "name": "レザージャケット", "image-url" : "https://.../ lether.jpg"}
