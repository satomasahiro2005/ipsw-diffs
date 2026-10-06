## ContextKit

> `/System/Library/PrivateFrameworks/ContextKit.framework/ContextKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf3c0` | `0xf5ac` | **`+0x1ec`** |
| `__TEXT.__oslogstring` | `0x937` | `0x9a3` | **`+0x6c`** |
| `__DATA.__bss` | `0x98` | `0xb8` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xbe0` | `0xbe8` | **`+0x8`** |
| `__TEXT.__const` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x104c` | `0x1054` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x4b8` | `0x4c0` | **`+0x8`** |

### Other Changes

```diff

-307.0.0.0.0
+308.0.0.0.0

-  Functions: 465
-  Symbols:   842
-  CStrings:  208
+  Functions: 467
+  Symbols:   848
+  CStrings:  209
Symbols:
+ +[CKContextXPCClient resetConnectionFailureTrackingForTesting]
+ _clock_gettime_nsec_np
+ _kConnectionFailureRunStartNs
+ _kConsecutiveConnectionFailures
+ _kFailFastUntilNs
+ _kLastConnectionFailureNs
Functions:
~ ___27-[CKContextRequest execute]_block_invoke.201 : 340 -> 356
~ ___38-[CKContextRequest _executeWithReply:]_block_invoke.210 : 284 -> 324
~ +[CKContextXPCClient isXPCConnectionError:] : 260 -> 528
+ +[CKContextXPCClient resetConnectionFailureTrackingForTesting]
~ +[CKContextXPCClient initialize].cold.1 : 72 -> 68
~ +[CKContextXPCClient isXPCConnectionError:].cold.1 : 72 -> 80
~ +[CKContextXPCClient isXPCConnectionError:].cold.2 : 72 -> 68
+ +[CKContextXPCClient isXPCConnectionError:].cold.3
CStrings:
+ "ContextService is not accepting connections; failing fast without retry: %@"
+ "XPC connection unusable after %lu consecutive failures, establishing new connection: %@"
- "XPC connection invalid, establishing new connection: %@"
```
