# OpenSSL Encryption

Encrypt:
openssl enc -aes-256-cbc -salt -in file.txt -out file.enc

Decrypt:
openssl enc -d -aes-256-cbc -in file.enc -out decrypted.txt

Symmetric Encryption uses same key.
Asymmetric Encryption uses public & private keys.
