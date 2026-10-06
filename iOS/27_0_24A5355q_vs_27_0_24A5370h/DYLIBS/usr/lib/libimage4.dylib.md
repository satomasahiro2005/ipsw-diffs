## libimage4.dylib

> `/usr/lib/libimage4.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b9e0` | `0x2bc40` | **`+0x260`** |
| `__DATA_CONST.__const` | `0x9b78` | `0x9b88` | **`+0x10`** |
| `__TEXT.__const` | `0x1ae30` | `0x1ae40` | **`+0x10`** |
| `__TEXT.__cstring` | `0x697a` | `0x697c` | **`+0x2`** |

### Other Changes

```diff

-372.0.0.0.0
+374.0.0.0.0

-  Functions: 1144
-  Symbols:   2678
+  Functions: 1145
+  Symbols:   2681
Symbols:
+ _CTParseLeafSPKI
+ __oidSmtpUTF8Mailbox
+ _oidSmtpUTF8Mailbox
Functions:
~ __image4_trust_post_properties : 332 -> 356
~ __image4_trust_find_record : 216 -> 232
~ __darwin_el0_alloc_type : 200 -> 232
~ __darwin_el0_alloc_data : 168 -> 196
~ __darwin_el0_query_trust_store : 476 -> 484
~ __darwin_el0_query_property_uint32 : 308 -> 304
~ __darwin_el0_query_property_uint64 : 164 -> 160
~ __darwin_runtime_alloc : 168 -> 196
~ _chip_bin_find_by_handle : 44 -> 68
~ __chip_decode_select_dynamic : 1772 -> 1788
~ _darwin_syscall_init : 248 -> 272
~ __closure_node_get_value_string : 448 -> 452
~ __restore_runtime_alloc : 168 -> 196
~ __fd_measure : 892 -> 900
~ _find_digest : 128 -> 140
~ _validateSignatureRSA : 640 -> 636
~ _validateSignatureEC : 600 -> 596
~ _compressECPublicKey : 412 -> 408
~ _decompressECPublicKey : 428 -> 424
~ _CMSParseImplicitCertificateSet : 708 -> 756
+ _CTParseLeafSPKI
~ _CTVerifyHostname : 164 -> 180
~ _CTCompareGeneralNameToHostname : 572 -> 564
~ _CTEvaluateKeyTransparency : 464 -> 472
~ _CTGetICDPFederationType : 288 -> 316
~ _CTEvaluateICDPFederation : 216 -> 236
~ _X509ChainParseCertificateSet : 392 -> 408
~ _verify_chain_img4_v1 : 720 -> 724
~ _verify_chain_img4_ec_v1 : 432 -> 436
~ _parse_ec_chain : 592 -> 588
~ _property_print_value.cold.1 : 80 -> 84
~ _version_copyout : 132 -> 136
CStrings:
+ "374"
+ "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Mon Jun 15 23:47:29 PDT 2026; root:AppleImage4_libraries-374~2133/libimage4/RELEASE_ARM64E"
+ "Darwin Image4 Library Version 7.0.0: Mon Jun 15 23:47:29 PDT 2026; root:AppleImage4_libraries-374~2133/libimage4/RELEASE_ARM64E"
- "372"
- "@(#)VERSION:Darwin Image4 Library Version 7.0.0: Thu May 21 06:16:14 PDT 2026; root:AppleImage4_libraries-372~221/libimage4/RELEASE_ARM64E"
- "Darwin Image4 Library Version 7.0.0: Thu May 21 06:16:14 PDT 2026; root:AppleImage4_libraries-372~221/libimage4/RELEASE_ARM64E"
```
