## Safety

> `/System/Library/Health/FeedItemPlugins/Safety.healthplugin/Safety`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb285c` | `0xb3168` | **`+0x90c`** |
| `__AUTH_CONST.__const` | `0x3318` | `0x3428` | **`+0x110`** |
| `__AUTH_CONST.__objc_const` | `0x46d8` | `0x47e0` | **`+0x108`** |
| `__DATA.__data` | `0x12a0` | `0x13a8` | **`+0x108`** |
| `__AUTH.__objc_data` | `0x1490` | `0x1550` | **`+0xc0`** |
| `__TEXT.__const` | `0x6fb4` | `0x7054` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x1d04` | `0x1d96` | **`+0x92`** |
| `__TEXT.__cstring` | `0x3738` | `0x37b8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x8ec` | `0x96c` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x30b8` | `0x3130` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x1c88` | `0x1cdc` | **`+0x54`** |
| `__DATA_CONST.__objc_selrefs` | `0xad0` | `0xb18` | **`+0x48`** |
| `__TEXT.__oslogstring` | `0x24ff` | `0x253f` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xb34` | `0xb74` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x2628` | `0x2660` | **`+0x38`** |
| `__DATA_DIRTY.__data` | `0x4318` | `0x4348` | **`+0x30`** |
| `__AUTH.__data` | `0x628` | `0x650` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x1fc8` | `0x1ff0` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x80` | `0xa0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x1a00` | `0x1a10` | **`+0x10`** |
| `__DATA_CONST.__objc_protorefs` | `0x40` | `0x50` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1cc9` | `0x1cd9` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x218` | `0x220` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x268` | `0x270` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x5e8` | `0x5ec` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0x44` | `0x48` | **`+0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 3147
-  Symbols:   328
-  CStrings:  476
+  Functions: 3164
+  Symbols:   330
+  CStrings:  479
Symbols:
+ _OBJC_CLASS_$_UNUserNotificationCenter
+ _kHKHealthAppBundleIdentifier
+ _swift_getFunctionTypeMetadata0
- _UIFontWeightBold
CStrings:
+ "HealthChecklistWorkProviding:pastPregnancyPhysiologicalWashoutDate"
+ "Safety/HealthChecklistUpdateAvailability.swift"
+ "[%s] Health notification settings changed; refreshing."
```
