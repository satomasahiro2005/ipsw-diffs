## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76fac` | `0x76e0c` | **`-0x1a0`** |
| `__AUTH_CONST.__const` | `0x8a0` | `0x8c0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x691c` | `0x6934` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1c58` | `0x1c68` | **`+0x10`** |
| `__DATA.__bss` | `0x210` | `0x220` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xa18` | `0xa20` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x3518` | `0x3520` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d38` | `0x1d40` | **`+0x8`** |

### Other Changes

```diff

-1242.0.0.0.0
+1244.0.0.0.0

-  Functions: 2342
-  Symbols:   5588
+  Functions: 2345
+  Symbols:   5595
Symbols:
+ +[CADXPCProxyHelper retriesForInvocation:]
+ _CFSetContainsValue
+ _CFSetCreate
+ __OBJC_$_CLASS_METHODS_CADXPCProxyHelper
+ ___42+[CADXPCProxyHelper retriesForInvocation:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64r_e17_v16?0"NSError"8ls32l8s40l8r64l8s48l8s56l8
+ _retriesForInvocation:.onceToken
+ _retriesForInvocation:.retryForbiddenSelectors
- ___block_descriptor_72_e8_32s40s48s56s64r_e17_v16?0"NSError"8ls32l8r64l8s40l8s48l8s56l8
```
