## libsystem_darwin.dylib

> `/usr/lib/system/libsystem_darwin.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65c4` | `0x65d8` | **`+0x14`** |
| `__TEXT.__const` | `0x90` | `0xa0` | **`+0x10`** |

### Other Changes

```diff

-1786.0.0.0.0
+1786.0.1.0.0
Functions:
~ _os_mach_msg_get_trailer -> _os_mach_msg_get_audit_trailer : 24 -> 48
~ _os_mach_msg_get_audit_trailer -> _os_mach_msg_get_trailer : 48 -> 24
~ _os_variant_check : 140 -> 160
```
