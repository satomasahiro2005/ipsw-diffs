## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/iCloudDriveCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x1740` | `0x17a8` | **`+0x68`** |
| `__TEXT.__text` | `0x306a58` | `0x306a2c` | **`-0x2c`** |

### Other Changes

```diff

-5140.0.0.0.0
+5140.0.0.0.2
Functions:
~ _BRCPrettyPrintEnumWithContext : 364 -> 368
~ _BRCPrettyPrintBitmapWithContext : 596 -> 572
~ +[BRCThrottle throttleHashFormat:] : 920 -> 900
~ ___brc_xattr_flags_from_name_block_invoke : 100 -> 96
```
