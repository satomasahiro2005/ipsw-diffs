## OSLog

> `/System/Library/Frameworks/OSLog.framework/OSLog`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaba0` | `0xab88` | **`-0x18`** |
| `__TEXT.__const` | `0xe8` | `0xd8` | **`-0x10`** |
| `__AUTH.__os_assumes_log` | `—` | `0x8` | **`+0x8`** |
| `__DATA_DIRTY.__os_assumes_log` | `0x8` | `—` | **`-0x8`** |

### Other Changes

```diff

-1958.0.0.0.1
+1965.0.0.0.0
Functions:
~ __timesync_repair : 1088 -> 1064
```
