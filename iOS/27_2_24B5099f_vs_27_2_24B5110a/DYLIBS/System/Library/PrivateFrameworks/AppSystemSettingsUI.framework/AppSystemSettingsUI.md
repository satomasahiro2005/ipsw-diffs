## AppSystemSettingsUI

> `/System/Library/PrivateFrameworks/AppSystemSettingsUI.framework/AppSystemSettingsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x260b4` | `0x27214` | **`+0x1160`** |
| `__TEXT.__cstring` | `0x263c` | `0x26ec` | **`+0xb0`** |
| `__TEXT.__unwind_info` | `0xa08` | `0xa48` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x730` | `0x768` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0xb78` | `0xba0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0xf98` | `0xfc0` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x16c0` | `0x16e0` | **`+0x20`** |
| `__DATA.__data` | `0x368` | `0x388` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xd7c` | `0xd9c` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x18b0` | `0x18c0` | **`+0x10`** |

### Other Changes

```diff

-2027.1.4.0.0
+2027.1.5.0.0

-  Functions: 760
-  Symbols:   1082
-  CStrings:  352
+  Functions: 773
+  Symbols:   1085
+  CStrings:  357
Symbols:
+ -[LSApplicationRecord(PSAdditions) au_supportsSuggestedActions]
+ _OBJC_CLASS_$_UIViewController
+ __OBJC_$_INSTANCE_METHODS_AUSystemSettingsSpecifiersProvider(Internal|AppSystemSettingsUI)
+ _swift_dynamicCastObjCClass
- __OBJC_$_INSTANCE_METHODS_AUSystemSettingsSpecifiersProvider(Internal)
CStrings:
+ "Suggested Actions"
+ "SuggestedActionsSettings"
+ "com.apple.MobileSMS"
+ "com.apple.developer.suggested-actions"
+ "com.apple.graphic-icon.suggested-actions"
```
