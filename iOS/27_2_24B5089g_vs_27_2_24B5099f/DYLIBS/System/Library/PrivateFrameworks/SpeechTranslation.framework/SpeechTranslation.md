## SpeechTranslation

> `/System/Library/PrivateFrameworks/SpeechTranslation.framework/SpeechTranslation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33978` | `0x33b84` | **`+0x20c`** |
| `__TEXT.__oslogstring` | `0x2ba5` | `0x2c35` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x13f4` | `0x1424` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x2638` | `0x2660` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xde8` | `0xe08` | **`+0x20`** |
| `__TEXT.__cstring` | `0x108a` | `0x10aa` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xcd8` | `0xcf0` | **`+0x18`** |
| `__DATA.__bss` | `0xc20` | `0xc30` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0xb08` | `0xb18` | **`+0x10`** |
| `__TEXT.__const` | `0xc7c` | `0xc6c` | **`-0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x50` | `0x58` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xcc` | `0xd0` | **`+0x4`** |

### Other Changes

```diff

-393.1.0.0.0
+396.0.0.0.0

-  Functions: 1030
-  Symbols:   1078
-  CStrings:  282
+  Functions: 1038
+  Symbols:   1088
+  CStrings:  284
Symbols:
+ -[STConversationalSpeechCoordinator .cxx_destruct]
+ -[STConversationalSpeechCoordinator _isSpeechToSpeechAvailableForSource:target:]
+ -[STConversationalSpeechCoordinator dealloc]
+ -[STConversationalSpeechCoordinator init]
+ _OBJC_IVAR_$_STConversationalSpeechCoordinator._aiLanguageStatus
+ __LTOSLogSTConversational
+ __LTOSLogSTConversational.log
+ __LTOSLogSTConversational.onceToken
+ __OBJC_$_INSTANCE_VARIABLES_STConversationalSpeechCoordinator
+ ____LTOSLogSTConversational_block_invoke
CStrings:
+ "%{public}@ registered for end-to-end routing, but this build has no turn coordinator — audio for this stream will be dropped, not translated"
+ "STConversational"
```
