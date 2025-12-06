
```mermaid
sequenceDiagram
    actor User
    participant Python_App as "Python App"
    participant private_pem as "private.pem"
    participant public_pem as "public.pem"

    User->>Python_App: generate_rsa_keypair()
    Python_App->>Python_App: RSA.generate(2048)
    Python_App->>Python_App: Export private, public key
    Python_App->>private_pem: Write private key
    Python_App->>public_pem: Write public key
    Python_App->>User: print("Kalitlar yaratildi: private.pem va public.pem")
    ```
