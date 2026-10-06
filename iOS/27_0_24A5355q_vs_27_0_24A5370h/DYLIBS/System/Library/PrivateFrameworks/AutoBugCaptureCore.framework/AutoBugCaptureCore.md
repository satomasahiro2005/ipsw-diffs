## AutoBugCaptureCore

> `/System/Library/PrivateFrameworks/AutoBugCaptureCore.framework/AutoBugCaptureCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0x6c40` | `0x6b40` | **`-0x100`** |
| `__TEXT.__text` | `0x77afc` | `0x77a24` | **`-0xd8`** |
| `__TEXT.__cstring` | `0x528f` | `0x51d5` | **`-0xba`** |
| `__DATA_CONST.__objc_arraydata` | `0x628` | `0x598` | **`-0x90`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x450` | `0x3f0` | **`-0x60`** |
| `__AUTH_CONST.__objc_dictobj` | `0x5a0` | `0x550` | **`-0x50`** |
| `__TEXT.__gcc_except_tab` | `0xdfc` | `0xdd0` | **`-0x2c`** |
| `__DATA_CONST.__const` | `0x2790` | `0x2768` | **`-0x28`** |
| `__AUTH_CONST.__const` | `0x640` | `0x620` | **`-0x20`** |
| `__AUTH_CONST.__objc_const` | `0xc890` | `0xc8b0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x5f94` | `0x5fac` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x820` | `0x830` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4f8` | `0x4e8` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1588` | `0x1578` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0xf0ac` | `0xf0b7` | **`+0xb`** |
| `__DATA_CONST.__objc_selrefs` | `0x3720` | `0x3728` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x68c` | `0x690` | **`+0x4`** |

### Other Changes

```diff

-460.0.0.0.0
+464.0.0.0.0

+  - /System/Library/PrivateFrameworks/DiagnosticExtensionsKit.framework/DiagnosticExtensionsKit

-  Functions: 2257
-  Symbols:   4312
-  CStrings:  2285
+  Functions: 2255
+  Symbols:   4311
+  CStrings:  2277
Symbols:
+ +[DiagnosticExtensionCaller newManager]
+ +[DiagnosticExtensionCaller safeguardTimeoutSeconds]
+ GCC_except_table6
+ _OBJC_CLASS_$_DEKExtensionManager
+ _OBJC_IVAR_$_DiagnosticExtensionCaller._liveDEsLock
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- GCC_except_table10
- GCC_except_table3
- _NSExtensionIdentifierName
- _NSExtensionPointName
- _OBJC_CLASS_$_DEExtension
- _OBJC_CLASS_$_NSExtension
- ___59-[DiagnosticExtensionCaller _getDEExtensionWithIdentifier:]_block_invoke
- ___block_descriptor_56_e8_32s40s48r_e29_v24?0"NSArray"8"NSError"16lr48l8s32l8s40l8
CStrings:
+ "%K == nil"
+ "Error discovering DE %@: %@"
+ "Found %lu accepted exception case%s in the past 24 hours, denying."
- "Error discovering extensions: %@"
- "Found %ld DEs that matched with the identifier %@."
- "Home Button"
- "On-Screen Affordance"
- "Raise To Speak"
- "SiriAssistant"
- "Voice"
- "client.request-failed"
- "com.apple.diagnosticextensions-service"
- "kAFAssistantErrorDomain.1_Carry"
- "kAFAssistantErrorDomain.1_NonCarry"
```
