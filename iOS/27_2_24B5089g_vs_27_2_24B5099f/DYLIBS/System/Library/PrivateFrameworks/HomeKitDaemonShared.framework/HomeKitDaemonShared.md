## HomeKitDaemonShared

> `/System/Library/PrivateFrameworks/HomeKitDaemonShared.framework/HomeKitDaemonShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc3e4` | `0xc7ac` | **`+0x3c8`** |
| `__TEXT.__oslogstring` | `0x19ef` | `0x1b8a` | **`+0x19b`** |
| `__TEXT.__objc_methlist` | `0xc04` | `0xc24` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x7b8` | `0x7d0` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x2f0` | `0x2f8` | **`+0x8`** |

### Other Changes

```diff

-1516.0.0.0.0
+1520.2.3.0.2

-  Functions: 286
-  Symbols:   629
-  CStrings:  169
+  Functions: 289
+  Symbols:   632
+  CStrings:  175
Symbols:
+ -[HMDStatusChannel _shouldRetryDeassertPresence]
+ -[HMDStatusChannel _startDeassertRetryTimer]
+ -[HMDStatusChannel _stopDeassertRetryTimer]
CStrings:
+ "Canceling the pending de-assert retry because a publish was requested"
+ "Not retrying the de-assert because publishing has resumed"
+ "Not retrying the de-assert because the channel is stopped"
+ "[%{public}@] Canceling the pending de-assert retry because a publish was requested"
+ "[%{public}@] Not retrying the de-assert because publishing has resumed"
+ "[%{public}@] Not retrying the de-assert because the channel is stopped"
```
