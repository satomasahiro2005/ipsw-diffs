## AppMigrationKit

> `/System/Library/Frameworks/AppMigrationKit.framework/AppMigrationKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77134` | `0x73df8` | **`-0x333c`** |
| `__TEXT.__eh_frame` | `0x6c60` | `0x68c8` | **`-0x398`** |
| `__TEXT.__unwind_info` | `0x2528` | `0x2488` | **`-0xa0`** |
| `__TEXT.__swift_as_cont` | `0x618` | `0x5e0` | **`-0x38`** |
| `__DATA.__data` | `0x1120` | `0x1150` | **`+0x30`** |
| `__TEXT.__const` | `0x50a0` | `0x5070` | **`-0x30`** |
| `__TEXT.__swift_as_entry` | `0x294` | `0x288` | **`-0xc`** |
| `__TEXT.__swift_as_ret` | `0x2a8` | `0x29c` | **`-0xc`** |

### Other Changes

```diff

-  Functions: 2563
+  Functions: 2532
Symbols:
+ ___swift_closure_destructor.24Tm
- ___swift_closure_destructor.28Tm
```
