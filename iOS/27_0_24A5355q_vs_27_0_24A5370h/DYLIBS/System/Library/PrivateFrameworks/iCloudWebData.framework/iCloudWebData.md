## iCloudWebData

> `/System/Library/PrivateFrameworks/iCloudWebData.framework/iCloudWebData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x213e8` | `0x216c8` | **`+0x2e0`** |
| `__TEXT.__eh_frame` | `0x1590` | `0x14d8` | **`-0xb8`** |
| `__AUTH_CONST.__auth_got` | `0x760` | `0x7a0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x910` | `0x8e0` | **`-0x30`** |
| `__AUTH_CONST.__const` | `0x2d0` | `0x2a8` | **`-0x28`** |
| `__DATA_CONST.__got` | `0x248` | `0x270` | **`+0x28`** |
| `__TEXT.__const` | `0x12dc` | `0x12b8` | **`-0x24`** |
| `__TEXT.__swift5_reflstr` | `0x2a4` | `0x283` | **`-0x21`** |
| `__TEXT.__swift5_capture` | `0x3c` | `0x28` | **`-0x14`** |
| `__DATA.__data` | `0x528` | `0x538` | **`+0x10`** |
| `__TEXT.__cstring` | `0x2bb` | `0x2ab` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x436` | `0x426` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x24c` | `0x240` | **`-0xc`** |
| `__TEXT.__swift_as_cont` | `0xa8` | `0x9c` | **`-0xc`** |
| `__AUTH.__data` | `0x618` | `0x610` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x48` | `0x40` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x4f4` | `0x4ec` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x88` | `0x80` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x72e` | `0x72a` | **`-0x4`** |

### Other Changes

```diff

-70.0.0.0.0
+71.1.0.0.0

-  Symbols:   282
+  Symbols:   284
Symbols:
+ ___swift_memcpy0_1
+ _objc_release_x23
+ _objc_release_x28
+ _swift_deallocPartialClassInstance
+ _symbolic _____ 9SwiftData12ModelContextC
+ _symbolic _____ 9SwiftData14ModelContainerC
- _objc_retain_x20
- _swift_retain_x10
- _symbolic _____Sg 9SwiftData12ModelContextC
- _symbolic _____Sg 9SwiftData14ModelContainerC
CStrings:
+ "PurgeStore - deleting all data from store."
+ "PurgeStore - failed erase attempt, retrying %@"
+ "PurgeStore - failed to delete existing data "
+ "PurgeStore - recreate model context"
- "Model Context missing"
- "PurgeStore - deleting the local store backing file."
- "PurgeStore - failed to delete existing database "
- "PurgeStore - recreate model container and context"
```
