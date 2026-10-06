## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8a8ac` | `0x8a9d0` | **`+0x124`** |
| `__TEXT.__oslogstring` | `0x4d41` | `0x4d70` | **`+0x2f`** |
| `__TEXT.__unwind_info` | `0x2a20` | `0x2a30` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xb60` | `0xb6c` | **`+0xc`** |
| `__TEXT.__cstring` | `0x58cd` | `0x58d6` | **`+0x9`** |
| `__TEXT.__objc_methlist` | `0xb494` | `0xb49c` | **`+0x8`** |

### Other Changes

```diff

-13.0.52.2.1
+13.1.12.0.0

-  Functions: 4702
-  Symbols:   7922
-  CStrings:  1422
+  Functions: 4704
+  Symbols:   7924
+  CStrings:  1423
Symbols:
+ -[ASDExtensionRequest _endRequestWithCancelCall:error:]
+ -[ASDExtensionRequest cancelRequestWithError:]
+ ___55-[ASDExtensionRequest _endRequestWithCancelCall:error:]_block_invoke
+ ___64-[ASDExtensionRequest _onRunQueue_tearDownWithCancelCall:error:]_block_invoke
- -[ASDExtensionRequest _endRequestWithCancelCall:]
- ___49-[ASDExtensionRequest _endRequestWithCancelCall:]_block_invoke
CStrings:
+ "ASDExtensionRequest cancel request: %{public}@"
+ "autoUpdateEnabled = %d"
- "CrashReporter"
```
