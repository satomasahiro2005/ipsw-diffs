## AccessoryNotifications

> `/System/Library/Frameworks/AccessoryNotifications.framework/AccessoryNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0xba8` | `0x1450` | **`+0x8a8`** |
| `__AUTH.__data` | `0x828` | `0x80` | **`-0x7a8`** |
| `__TEXT.__text` | `0x607e8` | `0x60cd4` | **`+0x4ec`** |
| `__AUTH.__objc_data` | `0x450` | `0xd8` | **`-0x378`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x378` | **`+0x378`** |
| `__DATA_DIRTY.__bss` | `0x4300` | `0x4500` | **`+0x200`** |
| `__DATA.__bss` | `0xcf00` | `0xcd80` | **`-0x180`** |
| `__DATA.__data` | `0x1430` | `0x1328` | **`-0x108`** |
| `__AUTH_CONST.__const` | `0x47f0` | `0x48b9` | **`+0xc9`** |
| `__TEXT.__const` | `0x9660` | `0x96ac` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0xefa` | `0xf44` | **`+0x4a`** |
| `__TEXT.__cstring` | `0x138d` | `0x13c1` | **`+0x34`** |
| `__TEXT.__eh_frame` | `0x2b30` | `0x2b58` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x1964` | `0x198c` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x428` | `0x448` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x1890` | `0x18ac` | **`+0x1c`** |
| `__TEXT.__swift5_typeref` | `0x226a` | `0x225d` | **`-0xd`** |
| `__TEXT.__swift5_reflstr` | `0xcb9` | `0xcc5` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0xb10` | `0xb18` | **`+0x8`** |
| `__DATA.__common` | `0x10` | `0x8` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1d70` | `0x1d78` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x898` | `0x89c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x248` | `0x24c` | **`+0x4`** |
| `__TEXT.__swift_as_cont` | `0x16c` | `0x170` | **`+0x4`** |

### Other Changes

```diff

-708.0.0.0.0
+713.0.0.0.0

+  - /System/Library/PrivateFrameworks/FeatureFlags.framework/FeatureFlags

-  Functions: 2565
-  Symbols:   1154
-  CStrings:  214
+  Functions: 2569
+  Symbols:   1155
+  CStrings:  217
Symbols:
+ ___swift_closure_destructor.174Tm
+ ___swift_exist.box.addr_destructor
+ ___swift_memcpy41_8
+ _symbolic _____ 22AccessoryNotifications0aB11FeatureFlagV
+ _symbolic _____ s12StaticStringV
+ _type_layout_string 22AccessoryNotifications0aB11FeatureFlagV
- ___swift_closure_destructor.176Tm
- _get_type_metadata 15Synchronization5MutexVy3XPC10XPCSessionCSgG noncopyable
- _get_type_metadata 15Synchronization5MutexVySayScCySo15NSXPCConnectionCs5Error_pGGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySo15NSXPCConnectionCSgG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "%s AccessoryNotifications feature flag disabled; not opening XPC session."
+ "AccessoryNotifications feature disabled."
+ "UserNotifications"
```
