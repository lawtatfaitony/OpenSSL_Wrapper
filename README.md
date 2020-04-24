# OpenSSL_Wrapper
很早期版本，只做参考，不做测试，否则浪费时间

Provides:

* RSA Sign/Verify

* AES Encrypt/Decrypt

* Many hash functions (SHA256 is given as example)

* Base64 Encoded/Decode

* URL Safe Base64 Alternative (Replaces unsafe url control characters with unused ones)

* Generating of PEM KeyPairs

* Writing PEM KeyPairs to file

* Display of PEM KeyPairs at runtime

* C++ std::string wrappers to all functions

To use the other hash functions simply change "SHA256" in the call to EVP_get_digestbyname to any other that openssl accepts
