# `jose` Modules API Documentation

> "JSON Web Almost Everything" - JWA, JWS, JWE, JWT, JWK, JWKS with no dependencies using runtime's native crypto.

## Support

If you or your business use `jose`, please consider becoming a [sponsor][support-sponsor] so I can continue maintaining it and adding new features carefree.

## Available modules

- JSON Web Tokens (JWT)
  - [Signing](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jwt_sign.SignJWT.md#readme)
  - [Verification & Claims Set Validation](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwt_verify.jwtVerify.md#readme)
  - Encrypted JSON Web Tokens
    - [Encryption](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jwt_encrypt.EncryptJWT.md#readme)
    - [Decryption & Claims Set Validation](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwt_decrypt.jwtDecrypt.md#readme)
- Key Import
  - [JWK Import](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_import.importJWK.md#readme)
  - [Public Key Import (SPKI)](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_import.importSPKI.md#readme)
  - [Public Key Import (X.509 Certificate)](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_import.importX509.md#readme)
  - [Private Key Import (PKCS #8)](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_import.importPKCS8.md#readme)
- JSON Web Encryption (JWE)
  - Encryption - [Compact](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jwe_compact_encrypt.CompactEncrypt.md#readme), [Flattened](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jwe_flattened_encrypt.FlattenedEncrypt.md#readme)
  - Decryption - [Compact](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwe_compact_decrypt.compactDecrypt.md#readme), [Flattened](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwe_flattened_decrypt.flattenedDecrypt.md#readme), [General](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwe_general_decrypt.generalDecrypt.md#readme)
- JSON Web Signature (JWS)
  - Signing - [Compact](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jws_compact_sign.CompactSign.md#readme), [Flattened](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jws_flattened_sign.FlattenedSign.md#readme), [General](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jws_general_sign.GeneralSign.md#readme)
  - Verification - [Compact](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jws_compact_verify.compactVerify.md#readme), [Flattened](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jws_flattened_verify.flattenedVerify.md#readme), [General](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jws_general_verify.generalVerify.md#readme)
- JSON Web Key (JWK)
  - [Thumbprints](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwk_thumbprint.calculateJwkThumbprint.md#readme)
  - [EmbeddedJWK](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwk_embedded.EmbeddedJWK.md#readme)
- JSON Web Key Set (JWKS)
  - [Verify using a remote JWKSet](https://github.com/panva/jose/blob/v4.1.0/docs/functions/jwks_remote.createRemoteJWKSet.md#readme)
- Key Pair or Secret Generation
  - [Asymmetric Key Pair Generation](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_generate_key_pair.generateKeyPair.md#readme)
  - [Symmetric Secret Generation](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_generate_secret.generateSecret.md#readme)
- Key Export
  - [JWK Export](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_export.exportJWK.md#readme)
  - [Private Key Export](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_export.exportPKCS8.md#readme)
  - [Public Key Export](https://github.com/panva/jose/blob/v4.1.0/docs/functions/key_export.exportSPKI.md#readme)
- Utilities
  - [Decoding Token's Protected Header](https://github.com/panva/jose/blob/v4.1.0/docs/functions/util_decode_protected_header.decodeProtectedHeader.md#readme)
- [Unsecured JWT](https://github.com/panva/jose/blob/v4.1.0/docs/classes/jwt_unsecured.UnsecuredJWT.md#readme)
- [JOSE Errors](https://github.com/panva/jose/blob/v4.1.0/docs/modules/util_errors.md#readme)

[support-sponsor]: https://github.com/sponsors/panva