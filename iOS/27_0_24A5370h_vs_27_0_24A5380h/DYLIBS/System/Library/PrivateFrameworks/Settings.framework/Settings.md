## Settings

> `/System/Library/PrivateFrameworks/Settings.framework/Settings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x130` | `0x1228` | **`+0x10f8`** |
| `__DATA_DIRTY.__objc_data` | `0x1260` | `0x168` | **`-0x10f8`** |
| `__DATA_DIRTY.__data` | `0x2718` | `0x1be8` | **`-0xb30`** |
| `__AUTH.__data` | `0x7e0` | `0x12c0` | **`+0xae0`** |
| `__TEXT.__text` | `0x90a28` | `0x90a04` | **`-0x24`** |
| `__TEXT.__const` | `0x6d40` | `0x6d50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2130` | `0x2140` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1628` | `0x1620` | **`-0x8`** |
| `__DATA_CONST.__const` | `0x4a0` | `0x4a8` | **`+0x8`** |

### Other Changes

```diff

-233.0.0.0.0
+2027.0.1.0.0

+  - /usr/lib/swift/libswiftCompression.dylib

-  Symbols:   1540
+  Symbols:   1541
Symbols:
+ __swift_FORCE_LOAD_$_swiftCompression
+ __swift_FORCE_LOAD_$_swiftCompression_$_Settings
- _swift_willThrowTypedImpl
```
