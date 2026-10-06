## AAAFoundation

> `/System/Library/PrivateFrameworks/AAAFoundation.framework/AAAFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x11dd4` | `0x11df0` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x1b3c` | `0x1b4c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1278` | `0x1280` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x6c0` | `0x6c8` | **`+0x8`** |

### Other Changes

```diff

-112.1.0.0.0
+113.0.0.0.0

-  Functions: 681
-  Symbols:   1433
+  Functions: 682
+  Symbols:   1434
Symbols:
+ -[AAFCertificateTrustValidator _isCertPinningDisabled]
Functions:
~ ___39-[AAFPromise _completeWithValue:error:]_block_invoke : 336 -> 332
~ -[NSData(AAAFoundation) aaf_toHexString] : 176 -> 192
~ -[AAFKeychainManager _unsafe_fetchKeychainItemsWithDescriptor:error:] : 716 -> 712
~ -[AAFService shouldAcceptNewConnection:] : 632 -> 628
~ -[AAFSerialization addSerializer:] : 388 -> 384
~ +[AAFResponseBodyRedactor redactedCopyForObject:forKeys:] : 740 -> 732
~ -[AAFCertificateTrustValidator _trySSLPinning:] : 204 -> 188
+ -[AAFCertificateTrustValidator _isCertPinningDisabled]
```
