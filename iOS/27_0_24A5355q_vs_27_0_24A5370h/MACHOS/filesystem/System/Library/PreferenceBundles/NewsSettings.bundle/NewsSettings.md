## NewsSettings

> `/System/Library/PreferenceBundles/NewsSettings.bundle/NewsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xd9e` | `0xe3e` | **`+0xa0`** |
| `__TEXT.__objc_methtype` | `0x24f` | `0x27f` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0x14c0` | `0x14a0` | **`-0x20`** |
| `__TEXT.__text` | `0x87d4` | `0x87ec` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1409` | `0x13f9` | **`-0x10`** |
| `__DATA.__objc_const` | `0x5d8` | `0x5d0` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x478` | `0x480` | **`+0x8`** |
| `__DATA_CONST.__const` | `0x738` | `0x730` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppSystemSettingsUI.framework/AppSystemSettingsUI

-  Functions: 148
-  Symbols:   315
-  CStrings:  400
+  Functions: 150
+  Symbols:   314
+  CStrings:  399
Symbols:
+ _OBJC_CLASS_$_AUSystemSettingsSpecifiersProvider
- _FRInternalExtrasProductName
- _OBJC_CLASS_$_PSSystemPolicyForApp
CStrings:
+ "@\"AUSystemSettingsSpecifiersProvider\""
+ "AUSystemSettingsSpecifiersProviderDelegate"
+ "T@\"AUSystemSettingsSpecifiersProvider\",&,N,V_systemSpecifiersProvider"
+ "_systemSpecifiersProvider"
+ "initWithApplicationBundleIdentifier:"
+ "presentViewController:animated:completion:"
+ "setSystemSpecifiersProvider:"
+ "systemSettingsSpecifiersProvider:presentViewController:animated:"
+ "systemSettingsSpecifiersProviderDidReloadSpecifiers:"
+ "systemSpecifiersProvider"
+ "v24@0:8@\"AUSystemSettingsSpecifiersProvider\"16"
+ "v36@0:8@\"AUSystemSettingsSpecifiersProvider\"16@\"UIViewController\"24B32"
+ "v36@0:8@16@24B32"
- "@\"PSSystemPolicyForApp\""
- "NewsInternalExtras"
- "PSSystemPolicyForAppDelegate"
- "T@\"PSSystemPolicyForApp\",&,N,V_appPolicy"
- "_appPolicy"
- "appPolicy"
- "initWithBundleIdentifier:"
- "setAppPolicy:"
- "showController:animate:"
- "systemPolicyForApp:didUpdateForSystemPolicyOptions:withValue:"
- "v28@0:8@\"UIViewController\"16B24"
- "v28@0:8@16B24"
- "v40@0:8@\"PSSystemPolicyForApp\"16Q24@32"
- "v40@0:8@16Q24@32"
```
