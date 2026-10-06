## AccountNotificationPlugin

> `/System/Library/Accounts/Notification/AccountNotificationPlugin.bundle/AccountNotificationPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x424` | `0x471` | **`+0x4d`** |
| `__TEXT.__text` | `0x80c` | `0x83c` | **`+0x30`** |
| `__TEXT.__objc_stubs` | `0x280` | `0x2a0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x38` | `0x48` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x188` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-291.125.4.0.0
+291.125.7.0.0
+  - /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation

-  Symbols:   39
-  CStrings:  99
+  Symbols:   41
+  CStrings:  100
Symbols:
+ _OBJC_CLASS_$_FARestrictionsManagementSettings
+ ___kCFBooleanTrue
Functions:
~ sub_ec0 -> sub_f20 : 204 -> 252
CStrings:
+ "restrictionsManagementSettingsWithIsManaged:hasStrictPolicy:"
+ "setRestrictions:managementSettings:completion:"
- "setRestrictionsWithCompletion:"
```
