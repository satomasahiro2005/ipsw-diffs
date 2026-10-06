## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/KnowledgeMonitor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e1a0` | `0x2e260` | **`+0xc0`** |
| `__AUTH_CONST.__cfstring` | `0x1fc0` | `0x1fe0` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x400` | `0x420` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xc88` | `0xca8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2498` | `0x24b0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x30fb` | `0x3111` | **`+0x16`** |
| `__DATA.__bss` | `0x10` | `0x20` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x3254` | `0x3264` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x640` | `0x648` | **`+0x8`** |

### Other Changes

```diff

-476.0.0.0.0
+477.0.1.0.0

-  Functions: 1247
-  Symbols:   2244
-  CStrings:  583
+  Functions: 1250
+  Symbols:   2249
+  CStrings:  584
Symbols:
+ -[_DKAssertionsPreventingRestartMonitor isIgnorableSleepPreventer:]
+ _OBJC_CLASS_$_NSRegularExpression
+ ___67-[_DKAssertionsPreventingRestartMonitor isIgnorableSleepPreventer:]_block_invoke
+ _isIgnorableSleepPreventer:.onceToken
+ _isIgnorableSleepPreventer:.usbxdciRegex
CStrings:
+ "^AppleT[0-9]+USBXDCI$"
```
