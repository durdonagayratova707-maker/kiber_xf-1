```mermaid
flowchart TD
    A[Boshlash]
    A --> B[RSA key generate(2048)]
    B --> C[Private key export]
    B --> D[Public key export]
    C --> E[private.pem faylga yozish]
    D --> F[public.pem faylga yozish]
    E --> G[Tugatish]
    F --> G[Tugatish]
```
