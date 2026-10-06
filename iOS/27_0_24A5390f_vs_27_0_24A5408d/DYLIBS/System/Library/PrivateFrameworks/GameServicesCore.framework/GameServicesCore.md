## GameServicesCore

> `/System/Library/PrivateFrameworks/GameServicesCore.framework/GameServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3359f0` | `0x33afe0` | **`+0x55f0`** |
| `__DATA.__bss` | `0x27b98` | `0x282b8` | **`+0x720`** |
| `__TEXT.__unwind_info` | `0x11960` | `0x112b0` | **`-0x6b0`** |
| `__TEXT.__const` | `0x27d50` | `0x282b0` | **`+0x560`** |
| `__TEXT.__eh_frame` | `0x30e5c` | `0x311c4` | **`+0x368`** |
| `__AUTH_CONST.__const` | `0x10250` | `0x10420` | **`+0x1d0`** |
| `__TEXT.__swift5_typeref` | `0xbb6c` | `0xbc66` | **`+0xfa`** |
| `__TEXT.__cstring` | `0x478f` | `0x486f` | **`+0xe0`** |
| `__TEXT.__swift5_fieldmd` | `0x7104` | `0x71bc` | **`+0xb8`** |
| `__TEXT.__constg_swiftt` | `0x694c` | `0x69f8` | **`+0xac`** |
| `__DATA.__data` | `0x4940` | `0x49c0` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0x4f26` | `0x4f96` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x708` | `0x758` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x3998` | `0x39d0` | **`+0x38`** |
| `__TEXT.__swift5_proto` | `0x1720` | `0x1758` | **`+0x38`** |
| `__DATA_DIRTY.__bss` | `0x65b0` | `0x6580` | **`-0x30`** |
| `__AUTH_CONST.__objc_const` | `0x5360` | `0x5338` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x2894` | `0x28b8` | **`+0x24`** |
| `__TEXT.__swift_as_ret` | `0x1a1c` | `0x1a40` | **`+0x24`** |
| `__DATA_CONST.__objc_selrefs` | `0x718` | `0x738` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x40c8` | `0x40e8` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x1128` | `0x1140` | **`+0x18`** |
| `__TEXT.__swift5_acfuncs` | `0xeb0` | `0xec4` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0x142c` | `0x1440` | **`+0x14`** |
| `__AUTH.__data` | `0x3890` | `0x38a0` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x744` | `0x750` | **`+0xc`** |
| `__DATA_DIRTY.__data` | `0x4470` | `0x4478` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x27c` | `0x274` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x12dc` | `0x12d8` | **`-0x4`** |
| `__TEXT.__swift5_protos` | `0x104` | `0x108` | **`+0x4`** |

### Other Changes

```diff

-821.0.20.0.0
+821.0.25.0.0

-  Functions: 21868
-  Symbols:   4478
-  CStrings:  821
+  Functions: 22015
+  Symbols:   4495
+  CStrings:  827
Symbols:
+ ___swift_closure_destructor.210Tm
+ _associated conformance 16GameServicesCore18LocalizableColumnsOSHAASQ
+ _associated conformance 16GameServicesCore18LocalizableColumnsOs9CodingKeyAAs23CustomStringConvertible
+ _associated conformance 16GameServicesCore18LocalizableColumnsOs9CodingKeyAAs28CustomDebugStringConvertible
+ _associated conformance 16GameServicesCore8LocaleIDV14GRDBv7Internal24DatabaseValueConvertibleAaD14SQLExpressible
+ _associated conformance 16GameServicesCore8LocaleIDV14GRDBv7Internal24DatabaseValueConvertibleAaD16StatementBinding
+ _associated conformance 16GameServicesCore8LocaleIDVSHAASQ
+ _generic environment 16GameServicesCore18GRDBSyncableEntityRzAA019LocalizableSyncableE0Rzl
+ _memset
+ _symbolic $s16GameServicesCore25LocalizableSyncableEntityP
+ _symbolic SaySbG
+ _symbolic Say_____y______pGGSayAAy______pGG___________pIetMHgTgTgzo_ 12GameServices3RefV AA0A0P AA6PlayerP 0aB4Core18AchievementServiceC s5ErrorP
+ _symbolic Shy_____G 16GameServicesCore8LocaleIDV
+ _symbolic _____ 16GameServicesCore18LocalizableColumnsO
+ _symbolic _____ 16GameServicesCore25AchievementProgressReportV
+ _symbolic _____ 16GameServicesCore8LocaleIDV
+ _symbolic _____ySSSaySiGG s18_DictionaryStorageC
+ _symbolic _____ySSSdG s17_NativeDictionaryV
+ _symbolic _____ySbG s23_ContiguousArrayStorageC
+ _symbolic _____y_____G s11_SetStorageC 16GameServicesCore8LocaleIDV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 16GameServicesCore25AchievementProgressReportV
+ _type_layout_string 16GameServicesCore25AchievementProgressReportV
+ _type_layout_string 16GameServicesCore8LocaleIDV
- ___swift_closure_destructor.206Tm
- _symbolic SS______t 16GameServicesCore25AchievementDescriptionRowV
- _symbolic _____ySS_____G s17_NativeDictionaryV 16GameServicesCore25AchievementDescriptionRowV
- _symbolic _____ySS_____G s18_DictionaryStorageC 14GRDBv7Internal12DatabasePoolC
- _symbolic _____ySS_____G s18_DictionaryStorageC 16GameServicesCore25AchievementDescriptionRowV
- _symbolic _____ySS______tG s23_ContiguousArrayStorageC 16GameServicesCore25AchievementDescriptionRowV
CStrings:
+ ": duplicate confirmed rows for entityId '"
+ "Failed to open shared GRDB pool (%s), deleting files: %@"
+ "Failed to present achievement banner for %s: %@"
+ "GameServicesCore/LocalizableSyncableEntity+GRDB.swift"
+ "Opened shared GRDB pool for player: %s"
+ "_on_entity_id_row_type_locale"
+ "a LocalizableSyncableEntity must use the locale-scoped fetch"
+ "achievement_descriptions_on_bundle_id_locale"
+ "locale"
- "Failed to open shared GRDB pool (%s, %s), deleting files: %@"
- "Opened shared GRDB pool for player: %s, language: %s"
- "achievement_descriptions_on_bundle_id"
```
