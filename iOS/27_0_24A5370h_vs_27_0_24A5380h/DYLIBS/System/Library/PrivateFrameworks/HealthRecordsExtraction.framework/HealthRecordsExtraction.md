## HealthRecordsExtraction

> `/System/Library/PrivateFrameworks/HealthRecordsExtraction.framework/HealthRecordsExtraction`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x141428` | `0x147f50` | **`+0x6b28`** |
| `__DATA.__bss` | `0x18bd0` | `0x199d0` | **`+0xe00`** |
| `__TEXT.__const` | `0xcea0` | `0xd7a0` | **`+0x900`** |
| `__AUTH_CONST.__const` | `0xef98` | `0xf720` | **`+0x788`** |
| `__TEXT.__eh_frame` | `0x6dfc` | `0x71d4` | **`+0x3d8`** |
| `__TEXT.__swift5_fieldmd` | `0x3a64` | `0x3c78` | **`+0x214`** |
| `__AUTH.__objc_data` | `0xf18` | `0xd38` | **`-0x1e0`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x1e0` | **`+0x1e0`** |
| `__TEXT.__swift5_reflstr` | `0x1e9c` | `0x1fec` | **`+0x150`** |
| `__TEXT.__cstring` | `0xc804` | `0xc93c` | **`+0x138`** |
| `__AUTH.__data` | `0x2078` | `0x1f58` | **`-0x120`** |
| `__TEXT.__constg_swiftt` | `0x21b8` | `0x22c0` | **`+0x108`** |
| `__AUTH_CONST.__auth_got` | `0x1268` | `0x12f8` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x1ae8` | `0x1b70` | **`+0x88`** |
| `__DATA.__data` | `0x2b80` | `0x2bf0` | **`+0x70`** |
| `__TEXT.__swift5_proto` | `0xce4` | `0xd54` | **`+0x70`** |
| `__TEXT.__swift5_assocty` | `0x498` | `0x4e0` | **`+0x48`** |
| `__TEXT.__swift5_builtin` | `0x154` | `0x190` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x4498` | `0x4468` | **`-0x30`** |
| `__TEXT.__swift5_types` | `0x308` | `0x330` | **`+0x28`** |
| `__TEXT.__swift5_mpenum` | `0x38` | `0x50` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x608` | `0x618` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xb28` | `0xb20` | **`-0x8`** |

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 5669
-  Symbols:   2155
-  CStrings:  1309
+  Functions: 5792
+  Symbols:   2185
+  CStrings:  1319
Symbols:
+ _adler32
+ _associated conformance 23HealthRecordsExtraction20CompressionAlgorithmOSHAASQ
+ _associated conformance 23HealthRecordsExtraction25CompressionAlgorithmErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 23HealthRecordsExtraction3JWEV10EncryptionOSHAASQ
+ _associated conformance 23HealthRecordsExtraction3JWEV6HeaderV10CodingKeys33_228D55C054C4053E9E30179F3493720ALLOSHAASQ
+ _associated conformance 23HealthRecordsExtraction3JWEV6HeaderV10CodingKeys33_228D55C054C4053E9E30179F3493720ALLOs0F3KeyAAs23CustomStringConvertible
+ _associated conformance 23HealthRecordsExtraction3JWEV6HeaderV10CodingKeys33_228D55C054C4053E9E30179F3493720ALLOs0F3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 23HealthRecordsExtraction3JWEV9AlgorithmOSHAASQ
+ _associated conformance 23HealthRecordsExtraction8JWEErrorO10Foundation14LocalizedErrorAAs0G0
+ _get_enum_tag_for_layout_string 23HealthRecordsExtraction10VCJWTErrorO
+ _get_enum_tag_for_layout_string 23HealthRecordsExtraction25CompressionAlgorithmErrorO
+ _get_enum_tag_for_layout_string 23HealthRecordsExtraction8JWEErrorO
+ _symbolic Say_____G s5UInt8V
+ _symbolic _____ 23HealthRecordsExtraction14Base64URLErrorO
+ _symbolic _____ 23HealthRecordsExtraction20CompressionAlgorithmO
+ _symbolic _____ 23HealthRecordsExtraction25CompressionAlgorithmErrorO
+ _symbolic _____ 23HealthRecordsExtraction3JWEV
+ _symbolic _____ 23HealthRecordsExtraction3JWEV10EncryptionO
+ _symbolic _____ 23HealthRecordsExtraction3JWEV6HeaderV
+ _symbolic _____ 23HealthRecordsExtraction3JWEV6HeaderV10CodingKeys33_228D55C054C4053E9E30179F3493720ALLO
+ _symbolic _____ 23HealthRecordsExtraction3JWEV9AlgorithmO
+ _symbolic _____ 23HealthRecordsExtraction8JWEErrorO
+ _symbolic _____ 23HealthRecordsExtraction9Base64URLV
+ _symbolic _____Sg 23HealthRecordsExtraction20CompressionAlgorithmO
+ _symbolic _____Sg 23HealthRecordsExtraction3JWEV10EncryptionO
+ _type_layout_string 23HealthRecordsExtraction10VCJWTErrorO
+ _type_layout_string 23HealthRecordsExtraction14Base64URLErrorO
+ _type_layout_string 23HealthRecordsExtraction25CompressionAlgorithmErrorO
+ _type_layout_string 23HealthRecordsExtraction27SignedClinicalDataJWTHeaderV
+ _type_layout_string 23HealthRecordsExtraction3JWEV
+ _type_layout_string 23HealthRecordsExtraction3JWEV6HeaderV
+ _type_layout_string 23HealthRecordsExtraction8JWEErrorO
- _symbolic _____ 20HealthRecordServices20CompressionAlgorithmO
- _symbolic _____Sg 20HealthRecordServices20CompressionAlgorithmO
CStrings:
+ "' is not supported"
+ "A256GCM"
+ "A256KW"
+ "DEF"
+ "Data appear truncated with length: "
+ "Invalid ZLib header: "
+ "Invalid checksum"
+ "The CEK encryption algorithm '"
+ "The shared key hasn't been supplied"
+ "Using injected nonce, rather than generating a new one. I hope you're just debugging!"
+ "dir"
- "com.apple.HealthKit"
```
