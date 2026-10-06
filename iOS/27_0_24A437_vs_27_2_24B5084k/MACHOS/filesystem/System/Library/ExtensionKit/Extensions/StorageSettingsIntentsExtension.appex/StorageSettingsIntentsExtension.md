## StorageSettingsIntentsExtension

> `/System/Library/ExtensionKit/Extensions/StorageSettingsIntentsExtension.appex/StorageSettingsIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3934` | `0x3dd0` | **`+0x49c`** |
| `__TEXT.__cstring` | `0x171` | `0x2b6` | **`+0x145`** |
| `__DATA.__bss` | `0x1020` | `0xf90` | **`-0x90`** |
| `__TEXT.__const` | `0xb38` | `0xaa8` | **`-0x90`** |
| `__TEXT.__auth_stubs` | `0x5c0` | `0x620` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x2a8` | `0x250` | **`-0x58`** |
| `__TEXT.__swift5_typeref` | `0x378` | `0x344` | **`-0x34`** |
| `__DATA_CONST.__auth_got` | `0x2e0` | `0x310` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x4e0` | `0x4b0` | **`-0x30`** |
| `__DATA.__data` | `0x1b0` | `0x188` | **`-0x28`** |
| `__TEXT.__eh_frame` | `0x250` | `0x278` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0xb4` | `0xa4` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x90` | `0x84` | **`-0xc`** |
| `__TEXT.__swift5_proto` | `0x80` | `0x7c` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x14` | `0x10` | **`-0x4`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x38` | **`-0x4`** |
| `__TEXT.__swift_as_ret` | `0x28` | `0x24` | **`-0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-177.0.0.0.0
+177.1.1.0.0

-  Functions: 166
-  Symbols:   58
-  CStrings:  10
+  Functions: 160
+  Symbols:   52
+  CStrings:  18
Symbols:
+ _MGGetStringAnswer
+ _memcpy
+ _objc_release_x21
+ _objc_release_x26
+ _swift_release_x8
- _swift_arrayInitWithCopy
- _swift_cvw_assignWithCopy
- _swift_cvw_assignWithTake
- _swift_cvw_destroy
- _swift_cvw_initWithCopy
- _swift_cvw_initializeBufferWithCopyOfBuffer
- _swift_errorRelease
- _swift_release_x24
- _swift_retain_x19
- _swift_retain_x20
- _swift_retain_x8
CStrings:
+ " SETTINGS_DEEPLINKS.ROOT.TITLE"
+ "#root"
+ "MarketingDeviceFamilyName"
+ "OPEN_SETTINGS_INTENT.TARGET.DESCRIPTION"
+ "OPEN_SETTINGS_INTENT.TARGET.TITLE"
+ "OPEN_SETTINGS_INTENT.TITLE"
+ "SETTINGS_DEEPLINKS.ROOT.SUBTITLE"
+ "SETTINGS_DEEPLINKS.ROOT.SYNONYM_0"
+ "SETTINGS_DEEPLINKS.ROOT.TITLE"
+ "SETTINGS_DEEPLINKS.TYPE_NAME"
+ "com.apple.Preferences"
+ "com.apple.graphic-icon.internal-drive"
+ "settings-navigation://com.apple.Settings.General/STORAGE_MGMT"
- "General → Storage"
- "com.apple.Settings"
- "com.apple.settings.Storage"
- "settings-navigation://com.apple.Settings.Storage"
- "storageSettings"
```
