## MatterPlugin

> `/System/Library/PrivateFrameworks/MatterPlugin.framework/MatterPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a158` | `0x4a318` | **`+0x1c0`** |
| `__DATA.__bss` | `0xa0` | `0xd0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x2c0` | `0x2e0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1218` | `0x1220` | **`+0x8`** |

### Other Changes

```diff

-84.0.0.0.0
+85.0.0.0.0

-  Functions: 1702
-  Symbols:   2747
+  Functions: 1705
+  Symbols:   2756
Symbols:
+ ____ensureAssociationMaps_block_invoke
+ __ensureAssociationMaps.onceToken
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _sControllerUUIDLock
+ _sControllerUUIDToClientType
+ _sControllerUUIDToSessionID
+ _sNodeIDLock
+ _sNodeIDToHomeUUID
```
