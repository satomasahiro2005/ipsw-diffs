## SiriProcessing

> `/System/Library/PrivateFrameworks/SiriProcessing.framework/SiriProcessing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd4304` | `0xd7a08` | **`+0x3704`** |
| `__DATA_DIRTY.__data` | `—` | `0x22a0` | **`+0x22a0`** |
| `__AUTH.__data` | `0x2e40` | `0x1350` | **`-0x1af0`** |
| `__DATA.__bss` | `0xd230` | `0xc5b0` | **`-0xc80`** |
| `__DATA_DIRTY.__bss` | `—` | `0xc80` | **`+0xc80`** |
| `__DATA.__data` | `0x23b8` | `0x1c78` | **`-0x740`** |
| `__AUTH.__objc_data` | `0x4e0` | `0x238` | **`-0x2a8`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x2a8` | **`+0x2a8`** |
| `__DATA_DIRTY.__common` | `—` | `0x148` | **`+0x148`** |
| `__DATA.__common` | `0x278` | `0x138` | **`-0x140`** |
| `__TEXT.__unwind_info` | `0x34c0` | `0x33c0` | **`-0x100`** |
| `__TEXT.__cstring` | `0xc90` | `0xd40` | **`+0xb0`** |
| `__AUTH_CONST.__objc_const` | `0x38a0` | `0x38e8` | **`+0x48`** |
| `__TEXT.__const` | `0x9f80` | `0x9fc0` | **`+0x40`** |
| `__TEXT.__eh_frame` | `0x8410` | `0x8440` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1400` | `0x1418` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x25f0` | `0x2608` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x2f02` | `0x2f14` | **`+0x12`** |
| `__TEXT.__oslogstring` | `0x2070` | `0x2080` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1cf2` | `0x1d02` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x820` | `0x828` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x2abc` | `0x2ab4` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x450` | `0x458` | **`+0x8`** |

### Other Changes

```diff

-2.9.0.0.0
+3.3.0.0.0

-  Functions: 3791
-  Symbols:   1576
-  CStrings:  241
+  Functions: 3797
+  Symbols:   1578
+  CStrings:  247
Symbols:
+ _swift_release_x13
+ _symbolic _____y__________G s18_DictionaryStorageC 14SiriProcessing11ComponentIdV 10Foundation4UUIDV
CStrings:
+ "Ingesting pure otel link: %s, timestamp: %s, clockId: %s"
+ "No alignable clock tracked for trace identifier edge from: %s to: %s timestamp: %s"
+ "Siri.MessageStaging"
+ "Siri.MessageTailing"
+ "Siri.Orchestrator"
+ "Siri.Preprocessor"
+ "Siri.SUTProcessor"
+ "Siri.SensitiveConditions"
+ "Siri.TextSubstitution"
+ "Siri.UnifiedStream"
+ "com.apple.unilog.processing"
- "Ingesting pure otel link: %s, timestamp: %s"
- "No alignable timestamp tracked for trace identifier edge from: %s to: %s timestamp: %s"
- "SensitiveConditions"
- "TextSubstitution"
- "com.apple.unilog.siri.processing"
```
