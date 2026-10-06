## SpeechTranslation

> `/System/Library/PrivateFrameworks/SpeechTranslation.framework/SpeechTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x32530` | `0x328b0` | **`+0x380`** |
| `__TEXT.__eh_frame` | `0xd98` | `0xde8` | **`+0x50`** |
| `__TEXT.__objc_methlist` | `0x12d4` | `0x1314` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x2b75` | `0x2ba5` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xa98` | `0xab8` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x2478` | `0x2488` | **`+0x10`** |
| `__DATA.__data` | `0xb38` | `0xb28` | **`-0x10`** |
| `__TEXT.__const` | `0xc7c` | `0xc6c` | **`-0x10`** |
| `__TEXT.__cstring` | `0x107a` | `0x108a` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xcc0` | `0xcd0` | **`+0x10`** |

### Other Changes

```diff

-385.0.0.0.0
+388.0.0.0.0

-  Functions: 1001
-  Symbols:   1051
-  CStrings:  281
+  Functions: 1007
+  Symbols:   1057
+  CStrings:  282
Symbols:
+ +[_STSELFLoggingClient sharedClient]
+ -[_STSELFLoggingClient _setUpOrReuseSessionWithConfiguration:]
+ -[_STSELFLoggingClient registerWithConfiguration:]
+ -[_STSpeechTranslatorManager selfLoggingClient]
+ __OBJC_$_CLASS_METHODS__STSELFLoggingClient
+ ___50-[_STSELFLoggingClient registerWithConfiguration:]_block_invoke
CStrings:
+ "Additional registration doesn't match language of ongoing logging session"
+ "Additional registration for ongoing session ignored."
+ "Register translator for instrumentation observation"
- "Additional client list doesn't match language of ongoing logging session"
- "Additional client list for ongoing session ignored."
```
