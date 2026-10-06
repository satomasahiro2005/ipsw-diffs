## libcoretls.dylib

> `/usr/lib/libcoretls.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12128` | `0x12154` | **`+0x2c`** |

### Other Changes

```text
Functions:
~ _SSLDecryptRecord : 880 -> 876
~ _tls_handshake_internal_prf : 472 -> 464
~ _HMAC_Alloc : 664 -> 668
~ _SSLEncodeUInt64 : 72 -> 76
~ _tls12ComputeFinishedMac : 332 -> 336
~ _SSLEncodeSize : 44 -> 36
~ _tls_record_encrypt : 960 -> 964
~ _tls_handshake_set_curves : 176 -> 196
~ _tls_handshake_set_sigalgs : 208 -> 216
~ _tls_handshake_set_ciphersuites_internal : 264 -> 276
~ _cipherSuiteInSet : 48 -> 56
~ _SelectNewCiphersuite : 240 -> 248
~ _ValidateSelectedCiphersuite : 84 -> 92
~ _sslDhKeyExchange : 352 -> 356
~ _debug_log_chain : 608 -> 588
~ _SSLEncodeCertificateRequest : 376 -> 368
~ _SSLProcessCertificateRequest : 872 -> 868
~ _SSLEncodeCertificateVerify : 832 -> 836
~ _tls_metric_client_finished : 1608 -> 1620
~ ___process_identifier_block_invoke : 304 -> 308
~ _SSLEncodeKeyExchange : 1132 -> 1128
~ _SSLGenServerECDHParamsAndKey : 184 -> 176
~ _SSLEncodeClientHello : 2468 -> 2444
~ _SSLProcessClientHello : 1156 -> 1176
~ _SSLProcessClientHelloExtensions : 1820 -> 1824
~ _SSLComputeMac : 1924 -> 1916
~ _copyHexString : 144 -> 140
~ _SSLProcessSSL2ClientHello : 616 -> 632
```
