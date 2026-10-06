## TipKit

> `/System/Library/Frameworks/TipKit.framework/TipKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__bss` | `0x2e90` | `0x2910` | **`-0x580`** |
| `__DATA_DIRTY.__bss` | `0x4130` | `0x46b0` | **`+0x580`** |
| `__DATA.__data` | `0x1100` | `0x10a0` | **`-0x60`** |
| `__DATA_DIRTY.__data` | `0x2768` | `0x27c8` | **`+0x60`** |
| `__TEXT.__text` | `0x7a930` | `0x7a8f0` | **`-0x40`** |
| `__TEXT.__const` | `0x66c0` | `0x66b0` | **`-0x10`** |
| `__DATA.__common` | `0x18` | `0x10` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xb28` | `0xb20` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x20` | `0x28` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x701b` | `0x7013` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x2718` | `0x2710` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 3972
-  Symbols:   1515
+  Functions: 3971
+  Symbols:   1512
Symbols:
+ _symbolic _____yxG 15Synchronization5MutexVAARi_zrlE
- _get_type_metadata SeRzSERzs8SendableRzl15Synchronization5MutexVy10TipKitCore0F9ParameterCSgG noncopyable
- _get_type_metadata SeRzSERzs8SendableRzl15Synchronization5MutexVyScTyyts5NeverOGSgG noncopyable
- _get_type_metadata SeRzSERzs8SendableRzl15Synchronization5MutexVyxG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
```
