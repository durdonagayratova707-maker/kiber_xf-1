```mermaid
flowchart TD
    A[Boshlash] --> B[Xabarni olish: input()]
    B --> C[Private keyni o‘qish: RSA.import_key]
    C --> D[Xesh yaratish: SHA256]
    D --> E[Imzo yaratish: pkcs1_15.sign]
    E --> F[Imzoni faylga yozish: signature.sig]
    F --> G[Tugatish]
```
