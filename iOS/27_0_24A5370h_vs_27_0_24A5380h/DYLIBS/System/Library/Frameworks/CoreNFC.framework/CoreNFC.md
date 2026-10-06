## CoreNFC

> `/System/Library/Frameworks/CoreNFC.framework/CoreNFC`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ed0c` | `0x3e700` | **`-0x60c`** |
| `__AUTH.__objc_data` | `0xef8` | `0xb88` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x370` | **`+0x370`** |
| `__AUTH_CONST.__cfstring` | `0xf20` | `0xd40` | **`-0x1e0`** |
| `__TEXT.__cstring` | `0x2e58` | `0x2d24` | **`-0x134`** |
| `__DATA.__objc_ivar` | `0x14c` | `0x118` | **`-0x34`** |
| `__DATA_DIRTY.__objc_ivar` | `—` | `0x34` | **`+0x34`** |
| `__DATA.__bss` | `0xbb0` | `0xb80` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `—` | `0x30` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x238` | `0x248` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xf00` | `0xef0` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xfc0` | `0xfb0` | **`-0x10`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  Symbols:   294
-  CStrings:  490
+  Symbols:   293
+  CStrings:  476
Symbols:
- _OBJC_CLASS_$_NSAssertionHandler
CStrings:
- "Delegate queue is nil"
- "Invalid UID length"
- "Missing session key"
- "NFCISO15693ReaderSessionTag.m"
- "NFCNDEFPayload.m"
- "NFCNDEFTag.m"
- "NFCTag.m"
- "Nil delegateQueue"
- "Nil hardwareManager"
- "Nil session"
- "Nil session queue"
- "Please use -wellKnownTypeTextPayloadWithString:locale: replacement"
- "Session queue is nil"
- "Unsupported poll mode"
```
