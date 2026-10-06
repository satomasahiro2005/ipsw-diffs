## HealthBalanceAppPluginBundle

> `/System/Library/Health/FeedItemPlugins/HealthBalanceAppPluginBundle.healthplugin/HealthBalanceAppPluginBundle`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x80` | `0xa0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x4c0` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x4c` | `0x5c` | **`+0x10`** |
| `__TEXT.__text` | `0x26d8` | `0x26e4` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0x28` | `0x30` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x270` | `0x268` | **`-0x8`** |
| `__TEXT.__const` | `0x1e2` | `0x1e4` | **`+0x2`** |
| `__TEXT.__cstring` | `0x51` | `0x53` | **`+0x2`** |
| `__TEXT.__objc_classname` | `0x1e9` | `0x1e8` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.72.2.7
+7027.1.36.2.7
+  - /System/Library/Frameworks/CoreServices.framework/CoreServices

+  - /System/Library/PrivateFrameworks/HealthAppServices.framework/HealthAppServices

-  Symbols:   87
-  CStrings:  18
+  Symbols:   86
+  CStrings:  19
Symbols:
+ _OBJC_CLASS_$_LSApplicationWorkspace
+ _OBJC_CLASS_$__TtC28HealthBalanceAppPluginBundle47_OvernightVitalsOutliersAlertTileViewController
+ _OBJC_METACLASS_$__TtC22HealthBalanceAppPlugin46OvernightVitalsOutliersAlertTileViewController
+ _OBJC_METACLASS_$__TtC28HealthBalanceAppPluginBundle47_OvernightVitalsOutliersAlertTileViewController
- _OBJC_CLASS_$_UIApplication
- _OBJC_CLASS_$__TtC28HealthBalanceAppPluginBundle45_SleepingSampleChangesAlertTileViewController
- _OBJC_METACLASS_$__TtC22HealthBalanceAppPlugin44SleepingSampleChangesAlertTileViewController
- _OBJC_METACLASS_$__TtC28HealthBalanceAppPluginBundle45_SleepingSampleChangesAlertTileViewController
- _objc_release_x24
Functions:
~ sub_1a9c -> sub_1b6c : 724 -> 736
~ sub_3404 -> sub_34e0 : 256 -> 264
~ sub_3504 -> sub_35e8 : 56 -> 48
~ sub_3a00 -> sub_3adc : 264 -> 256
~ sub_3b08 -> sub_3bdc : 48 -> 56
CStrings:
+ "HealthBalanceAppPluginBundle/_OvernightVitalsOutliersAlertTileViewController.swift"
+ "_TtC28HealthBalanceAppPluginBundle37_OvernightVitalsHelpTileActionHandler"
+ "_TtC28HealthBalanceAppPluginBundle47_OvernightVitalsOutliersAlertTileViewController"
+ "defaultWorkspace"
+ "hk_asyncOpenURL:"
- "HealthBalanceAppPluginBundle/_SleepingSampleChangesAlertTileViewController.swift"
- "_TtC28HealthBalanceAppPluginBundle36_SleepingSampleHelpTileActionHandler"
- "_TtC28HealthBalanceAppPluginBundle45_SleepingSampleChangesAlertTileViewController"
- "sharedApplication"
```
