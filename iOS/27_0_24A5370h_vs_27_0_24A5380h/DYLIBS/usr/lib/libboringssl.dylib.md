## libboringssl.dylib

> `/usr/lib/libboringssl.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa3414` | `0xa344c` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0x220` | `0x218` | **`-0x8`** |

### Other Changes

```text
Functions:
~ __ZN4bsslL26ssl_cipher_process_rulestrEPKcPPNS_15cipher_order_stES4_b : 1600 -> 1632
~ _SSL_get_group_name : 60 -> 72
~ __ZN4bssl28ssl_parse_serverhello_tlsextEPNS_13SSL_HANDSHAKEEPK6cbs_st : 748 -> 756
~ __ZN4bssl27ssl_pkey_supports_algorithmEPK6ssl_stP11evp_pkey_sttb : 360 -> 368
~ _boringssl_ciphers_create_set_bitmask : 156 -> 164
~ _RSA_verify_PKCS1_PSS_mgf1 : 888 -> 924
~ __ZN4bssl25tls13_process_certificateEPNS_13SSL_HANDSHAKEERKNS_10SSLMessageEb : 2792 -> 2800
~ __ZN4bssl20ssl_name_to_group_idEPtPKcm : 192 -> 204
~ __ZL16set_sigalg_prefsPN4bssl5ArrayItEENS_4SpanIKtEE : 584 -> 568
~ __ZN4bssl22tls13_server_handshakeEPNS_13SSL_HANDSHAKEE : 8860 -> 8852
~ _parse_base128_integer : 108 -> 104
~ __ZN4bssl20ssl_server_handshakeEPNS_13SSL_HANDSHAKEE : 11108 -> 11100
~ _SSL_CREDENTIAL_set1_PAKE_client_password_record : 228 -> 220
~ _SSL_SESSION_get_version : 68 -> 72
~ _BN_sub_word : 260 -> 268
~ __ZN4bsslL32tls13_add_compressed_certificateEP6ssl_stPNS_8internal14StackAllocatedI6cbb_stvXadL_Z8CBB_zeroEEXadL_Z11CBB_cleanupEEEEPNS_13SSL_HANDSHAKEEPS4_S9_PPhPm : 768 -> 760
~ __ZN4bssl34ssl_get_local_application_settingsEPKNS_13SSL_HANDSHAKEEPNS_4SpanIKhEES5_ : 152 -> 144
~ __ZN4bssl28ssl_parse_clienthello_tlsextEPNS_13SSL_HANDSHAKEEPK22ssl_early_callback_ctx : 724 -> 732
~ _bn_sqr_normal : 276 -> 256
~ __ZN4bssl19ssl_nid_to_group_idEPti : 68 -> 72
~ _tls1_sha256_final_raw : 72 -> 68
~ _tls1_sha512_final_raw : 116 -> 112
~ _OPENSSL_strlcat : 96 -> 92
```
