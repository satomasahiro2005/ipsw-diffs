## ActivityAchievementsUI

> `/System/Library/PrivateFrameworks/ActivityAchievementsUI.framework/ActivityAchievementsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35a44` | `0x35ac4` | **`+0x80`** |
| `__AUTH_CONST.__objc_const` | `0x3528` | `0x3508` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x18c0` | `0x18a8` | **`-0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x18f0` | `0x18e0` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2027.0.22.0.0
+2027.1.3.0.0

-  Functions: 1219
-  Symbols:   1432
+  Functions: 1217
+  Symbols:   1430
Symbols:
+ -[AAUIBadgeImageFactory _queue_earnedBadgeRenderer]
+ -[AAUIBadgeImageFactory _queue_unearnedBadgeRenderer]
+ GCC_except_table15
+ GCC_except_table18
- -[AAUIBadgeImageFactory earnedBadgeRenderer]
- -[AAUIBadgeImageFactory setEarnedBadgeRenderer:]
- -[AAUIBadgeImageFactory setUnearnedBadgeRenderer:]
- -[AAUIBadgeImageFactory unearnedBadgeRenderer]
- GCC_except_table13
- GCC_except_table16
```
