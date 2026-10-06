## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2ffd0` | `0x300a8` | **`+0xd8`** |
| `__TEXT.__oslogstring` | `0x5939` | `0x59a7` | **`+0x6e`** |
| `__TEXT.__const` | `0x414` | `0x424` | **`+0x10`** |
| `__TEXT.__cstring` | `0x3c41` | `0x3c45` | **`+0x4`** |

### Other Changes

```diff

-833.0.0.0.0
+833.0.3.0.0

-  CStrings:  904
+  CStrings:  905
Functions:
~ _container_persona_copy_from_voucher_proximate : 644 -> 636
~ _container_traverse_directory : 4156 -> 4188
~ __container_traverse_parse_attr_buf : 3512 -> 3700
~ _container_audit_token_get_launch_persona : 524 -> 528
CStrings:
+ "@(#)VERSION:Container Manager: Jul  8 2026 00:24:25; MobileContainerManager_system-833.0.3~133/arm64e"
+ "Malformed attrlist on entry in [%s]; length (%u) exceeds remaining buffer (%zu); buffer = %p, buffer_end = %p"
- "@(#)VERSION:Container Manager: Jun 23 2026 01:24:57; MobileContainerManager_system-833~403/arm64e"
```
