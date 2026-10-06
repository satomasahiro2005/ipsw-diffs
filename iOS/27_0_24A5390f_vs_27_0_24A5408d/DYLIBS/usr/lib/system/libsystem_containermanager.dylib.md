## libsystem_containermanager.dylib

> `/usr/lib/system/libsystem_containermanager.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x59a7` | `0x59cf` | **`+0x28`** |
| `__TEXT.__const` | `0x424` | `0x434` | **`+0x10`** |
| `__AUTH.__data` | `0x470` | `0x478` | **`+0x8`** |
| `__DATA.__bss` | `0x4d8` | `0x4e0` | **`+0x8`** |
| `__TEXT.__cstring` | `0x3c45` | `0x3c49` | **`+0x4`** |
| `__TEXT.__text` | `0x300a8` | `0x300a4` | **`-0x4`** |

### Other Changes

```diff

-833.0.3.0.0
+833.0.8.0.1

-  Symbols:   1008
+  Symbols:   1009
Symbols:
+ _setxattr
Functions:
~ ___container_create_or_lookup_app_group_path_by_app_group_identifier_block_invoke : 2268 -> 2256
~ __common_bundle_lookup : 1920 -> 1928
CStrings:
+ "@(#)VERSION:Container Manager: Aug  3 2026 21:12:57; MobileContainerManager_system-833.0.8.0.1~151/arm64e"
+ "Could not decode message into container object: 🔒%{private}s"
+ "Failed to issue sandbox extension to [🔒%{private}s] for containermanagerd"
+ "Requesting container lookup; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], bundle = [🔒%{private}s], root = [🔒%{private}s], executable = [🔒%{private}s], flags = %llu, euid = %u, uid = %u"
+ "Unable to get bundle from [🔒%{private}s]"
+ "Unable to get bundle root path from bundle at [🔒%{private}s]: %{public}d"
+ "Unable to get executable path from bundle at [🔒%{private}s]: %{public}d"
- "@(#)VERSION:Container Manager: Jul  8 2026 00:24:25; MobileContainerManager_system-833.0.3~133/arm64e"
- "Could not decode message into container object: %{public}s"
- "Failed to issue sandbox extension to [%{public}s] for containermanagerd"
- "Requesting container lookup; personaid = %u, type = %{public}s, name = %{public}s, origin [pid = %d, personaid = %u], proximate [pid = %d, personaid = %u], bundle = [%{public}s], root = [%{public}s], executable = [%{public}s], flags = %llu, euid = %u, uid = %u"
- "Unable to get bundle from [%{public}s]"
- "Unable to get bundle root path from bundle at [%{public}s]: %{public}d"
- "Unable to get executable path from bundle at [%{public}s]: %{public}d"
```
