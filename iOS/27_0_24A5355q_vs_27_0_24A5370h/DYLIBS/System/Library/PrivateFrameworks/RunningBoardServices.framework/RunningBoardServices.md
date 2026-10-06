## RunningBoardServices

> `/System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x41938` | `0x41b00` | **`+0x1c8`** |
| `__TEXT.__oslogstring` | `0x2722` | `0x27cb` | **`+0xa9`** |
| `__AUTH_CONST.__objc_const` | `0xafa8` | `0xb018` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x5b88` | `0x5b98` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x5d8` | `0x5e4` | **`+0xc`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d58` | `0x1d60` | **`+0x8`** |
| `__TEXT.__const` | `0x148` | `0x140` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x17b8` | `0x17c0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1066.0.0.0.1
+1071.0.0.0.0

-  Functions: 2324
-  Symbols:   3996
-  CStrings:  1060
+  Functions: 2328
+  Symbols:   4000
+  CStrings:  1063
Symbols:
+ -[RBSLaunchContext applicationRecord]
+ _OBJC_IVAR_$_RBSLaunchContext._applicationRecord
+ _OBJC_IVAR_$_RBSLaunchContext._applicationRecordComputed
+ _OBJC_IVAR_$_RBSLaunchContext._applicationRecordLock
CStrings:
+ "Could not create LSApplicationRecord from bundleID %@: %{public}@"
+ "Could not get bundle ID from %{public}@"
+ "unable to find LSApplicationRecord for identity %@: %{public}@"
```
