## SPRCore

> `/System/Library/PrivateFrameworks/SPRCore.framework/SPRCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22c88` | `0x23138` | **`+0x4b0`** |
| `__DATA_DIRTY.__data` | `0xd8` | `0x378` | **`+0x2a0`** |
| `__AUTH.__data` | `0x2a0` | `0xa8` | **`-0x1f8`** |
| `__TEXT.__eh_frame` | `0x1258` | `0x1350` | **`+0xf8`** |
| `__AUTH_CONST.__objc_const` | `0x5a0` | `0x658` | **`+0xb8`** |
| `__AUTH.__objc_data` | `0x50` | `—` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0xb58` | `0xba0` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x454` | `0x498` | **`+0x44`** |
| `__TEXT.__unwind_info` | `0x918` | `0x958` | **`+0x40`** |
| `__TEXT.__const` | `0x1024` | `0x1054` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x1e0` | `0x1f0` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x320` | `0x328` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x58` | `0x60` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x50` | `0x54` | **`+0x4`** |

### Other Changes

```diff

-50.30.0.0.0
+50.31.1.0.0

+  - /usr/lib/swift/libswiftDarwin.dylib

-  Functions: 821
-  Symbols:   209
+  Functions: 832
+  Symbols:   213
Symbols:
+ _OBJC_CLASS_$_NSFileManager
+ _close
+ _objc_release_x27
+ _swift_deallocPartialClassInstance
```
