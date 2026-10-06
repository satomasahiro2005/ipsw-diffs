## libnwswifttls.dylib

> `/usr/lib/libnwswifttls.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf9530` | `0xf98e0` | **`+0x3b0`** |
| `__TEXT.__cstring` | `0x1776` | `0x1836` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x3fb8` | `0x3fe8` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2657` | `0x2677` | **`+0x20`** |
| `__TEXT.__const` | `0x71d4` | `0x71e4` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x28c8` | `0x28d8` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x2b94` | `0x2ba0` | **`+0xc`** |

### Other Changes

```diff

-171.0.15.0.0
+171.40.7.0.0

-  Functions: 3683
-  Symbols:   8325
-  CStrings:  524
+  Functions: 3687
+  Symbols:   8329
+  CStrings:  527
Symbols:
+ _$s15SwiftTLSLibrary16TLSRecordHandlerV31setReadSequenceNumberForTestingyys6UInt64VF
+ _$s15SwiftTLSLibrary16TLSRecordHandlerV32setWriteSequenceNumberForTestingyys6UInt64VF
+ _$s15SwiftTLSLibrary18TLSRecordProtectorV15aeadRecordLimits6UInt64VyAA8TLSErrorOYKF
+ _$s15SwiftTLSLibrary18TLSRecordProtectorV28setSequenceNumbersForTesting5write4readys6UInt64VSg_AItF
CStrings:
+ "Unexpectedly parsed ciphertext when expecting plaintext"
+ "Unexpectedly parsed plaintext when expecting ciphertext"
+ "can't check key usage limit without ciphersuite set"
```
