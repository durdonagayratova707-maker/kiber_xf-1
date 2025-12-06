```mermaid
    A[Boshlash] --> B[Xabarni olish<br/>message = input()]
    B --> C[Private keyni o‘qish<br/>RSA.import_key()]
    C --> D[Xabarni xeshlash<br/>SHA256.new(message)]
    D --> E[Imzo yaratish<br/>pkcs1_15.sign(h)]
    E --> F[Imzoni faylga yozish<br/>signature.sig]
    F --> G[Tugatish<br/>"Xabar imzolandi!"]
```
