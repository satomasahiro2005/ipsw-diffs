## libsystem_kernel.dylib

> `/usr/lib/system/libsystem_kernel.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34f30` | `0x34f58` | **`+0x28`** |
| `__TEXT.__const` | `0xc90` | `0xc80` | **`-0x10`** |

### Other Changes

```diff

-13432.0.94.502.2
+13432.2.4.502.1
Functions:
~ _mach_vm_reclaim_try_enter : 416 -> 436
~ _posix_spawnattr_set_shared_region_config_np : 156 -> 168
~ _posix_spawnattr_get_shared_region_config_np : 72 -> 80
```
