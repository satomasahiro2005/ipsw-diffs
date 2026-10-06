## PhotoFoundation

> `/System/Library/PrivateFrameworks/PhotoFoundation.framework/PhotoFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x1b0` | `0x810` | **`+0x660`** |
| `__AUTH.__data` | `0x420` | `—` | **`-0x420`** |
| `__DATA.__data` | `0xb68` | `0x928` | **`-0x240`** |
| `__TEXT.__text` | `0x23f74` | `0x240e8` | **`+0x174`** |
| `__AUTH.__objc_data` | `0xb8` | `—` | **`-0xb8`** |
| `__DATA_DIRTY.__objc_data` | `0x800` | `0x8b8` | **`+0xb8`** |
| `__AUTH_CONST.__auth_got` | `0xe38` | `0xe48` | **`+0x10`** |
| `__TEXT.__const` | `0x22d8` | `0x22e8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x418` | `0x420` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdc8` | `0xdd0` | **`+0x8`** |

### Other Changes

```diff

-916.40.110.0.0
+916.45.110.0.0

-  Functions: 1496
-  Symbols:   1349
+  Functions: 1497
+  Symbols:   1353
Symbols:
+ _PFGetHeapStatistics
+ _mach_task_self_
+ _malloc_get_all_zones
+ _malloc_zone_statistics
```
