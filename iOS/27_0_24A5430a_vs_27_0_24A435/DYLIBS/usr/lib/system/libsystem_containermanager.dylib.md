## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x300a4` | `0x300b8` | **`+0x14`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff
Functions:
~ _container_perfect_hash_index_of : 1532 -> 1536
~ _container_string_rom_create : 2728 -> 2740
~ ___container_string_rom_create_block_invoke : 292 -> 296
CStrings:
+ "@(#)VERSION:Container Manager: Aug  8 2026 13:52:04; MobileContainerManager_system-833.0.8.0.1~205/arm64e"
- "@(#)VERSION:Container Manager: Aug  8 2026 17:00:47; MobileContainerManager_system-833.0.8.0.1~212/arm64e"
```
