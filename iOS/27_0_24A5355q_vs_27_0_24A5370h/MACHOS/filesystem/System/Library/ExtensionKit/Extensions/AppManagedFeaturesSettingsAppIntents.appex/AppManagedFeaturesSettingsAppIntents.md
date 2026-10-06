## AppManagedFeaturesSettingsAppIntents

> `/System/Library/ExtensionKit/Extensions/AppManagedFeaturesSettingsAppIntents.appex/AppManagedFeaturesSettingsAppIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d5c` | `0x3e18` | **`+0xbc`** |
| `__TEXT.__cstring` | `0x143` | `0x100` | **`-0x43`** |
| `__TEXT.__auth_stubs` | `0x4e0` | `0x500` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x280` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-43.0.0.0.0
+46.0.1.0.0

-  CStrings:  16
+  CStrings:  15
Functions:
~ sub_100003f74 : 100 -> 288
CStrings:
+ "Managed Financing"
+ "Managed Financing Settings"
+ "Open Managed Financing Settings"
- "App Managed Features Settings"
- "Managed Features"
- "Open App Managed Features Settings"
- "settings-navigation://com.apple.Settings.General/SAFE_FINANCING"
```
