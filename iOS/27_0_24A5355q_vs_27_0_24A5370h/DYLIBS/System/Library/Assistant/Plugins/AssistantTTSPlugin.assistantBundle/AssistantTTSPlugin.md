## AssistantTTSPlugin

> `/System/Library/Assistant/Plugins/AssistantTTSPlugin.assistantBundle/AssistantTTSPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x0` | `0xc8` | **`+0xc8`** |
| `__TEXT.__text` | `0xb04` | `0xb94` | **`+0x90`** |
| `__AUTH_CONST.__const` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__const` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1e4` | `0x1fc` | **`+0x18`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x78` | `0x80` | **`+0x8`** |
| `__TEXT.__cstring` | `0x39` | `0x3f` | **`+0x6`** |

### Other Changes

```diff

-3600.8.1.0.0
+3600.12.1.0.0

+  - /System/Library/PrivateFrameworks/SiriTTSService.framework/SiriTTSService

-  Functions: 11
-  Symbols:   60
-  CStrings:  5
+  Functions: 13
+  Symbols:   66
+  CStrings:  6
Symbols:
+ _OBJC_CLASS_$_SiriTTSDaemonSession
+ _OBJC_CLASS_$_SiriTTSDurationEstimator
+ _OBJC_CLASS_$_SiriTTSSynthesisRequest
+ _OBJC_CLASS_$_SiriTTSSynthesisVoice
+ __NSConcreteGlobalBlock
+ _dispatch_once
+ _objc_release_x1
+ _objc_retainAutoreleaseReturnValue
+ _objc_retain_x19
- _OBJC_CLASS_$_VSSpeechRequest
- _OBJC_CLASS_$_VSSpeechSynthesizer
- _objc_retain_x28
CStrings:
+ "v8@?0"
```
