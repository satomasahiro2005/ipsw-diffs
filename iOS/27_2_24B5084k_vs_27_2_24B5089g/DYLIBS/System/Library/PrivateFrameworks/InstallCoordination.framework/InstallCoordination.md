## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/InstallCoordination`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6f2c0` | `0x6f374` | **`+0xb4`** |
| `__DATA_CONST.__objc_selrefs` | `0x2458` | `0x2470` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x4b90` | `0x4ba0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x510` | `0x518` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1b58` | `0x1b60` | **`+0x8`** |

### Other Changes

```diff

-849.40.2.502.1
+849.40.4.0.1

+  - /System/Library/PrivateFrameworks/AppProtection.framework/AppProtection

-  Functions: 2277
-  Symbols:   3179
+  Functions: 2278
+  Symbols:   3181
Symbols:
+ +[IXAppInstallCoordinator(IXAppReplacement) _appIsHidden:]
+ GCC_except_table19
+ _OBJC_CLASS_$_APApplication
- GCC_except_table12
```
