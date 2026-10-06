## NotesSettings

> `/System/Library/PreferenceBundles/NotesSettings.bundle/NotesSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe080` | `0xdd0c` | **`-0x374`** |
| `__TEXT.__objc_stubs` | `0x2d20` | `0x2b20` | **`-0x200`** |
| `__DATA.__objc_const` | `0x1420` | `0x1290` | **`-0x190`** |
| `__DATA.__objc_data` | `0x640` | `0x550` | **`-0xf0`** |
| `__TEXT.__objc_methtype` | `0x436` | `0x4e3` | **`+0xad`** |
| `__TEXT.__objc_methname` | `0x3452` | `0x33e4` | **`-0x6e`** |
| `__DATA.__objc_selrefs` | `0xe60` | `0xdf8` | **`-0x68`** |
| `__DATA.__data` | `0x208` | `0x268` | **`+0x60`** |
| `__TEXT.__objc_classname` | `0x319` | `0x2e9` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0xbf4` | `0xbc4` | **`-0x30`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0x90` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x3a8` | `0x390` | **`-0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x18` | `0x20` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x88` | `0x80` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_ivar`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-2985.0.0.202.2
+2991.0.0.0.0

+  - /System/Library/PrivateFrameworks/AppSystemSettingsUI.framework/AppSystemSettingsUI

-  Functions: 257
+  Functions: 253

-  CStrings:  886
+  CStrings:  875
Symbols:
+ _OBJC_CLASS_$_AUSystemSettingsSpecifiersProvider
- _OBJC_CLASS_$_UIScreen
CStrings:
+ "@\"AUSystemSettingsSpecifiersProvider\""
+ "AUSystemSettingsSpecifiersProviderDelegate"
+ "T@\"AUSystemSettingsSpecifiersProvider\",&,N,V_systemSettingsSpecifiersProvider"
+ "_systemSettingsSpecifiersProvider"
+ "initWithApplicationBundleIdentifier:"
+ "setSystemSettingsSpecifiersProvider:"
+ "systemSettingsSpecifiersProvider"
+ "systemSettingsSpecifiersProvider:presentViewController:animated:"
+ "systemSettingsSpecifiersProviderDidReloadSpecifiers:"
+ "v24@0:8@\"AUSystemSettingsSpecifiersProvider\"16"
+ "v36@0:8@\"AUSystemSettingsSpecifiersProvider\"16@\"UIViewController\"24B32"
+ "v36@0:8@16@24B32"
- "ICSinglePixelHorizontalLineView"
- "ICSinglePixelLineView"
- "ICSinglePixelVerticalLineView"
- "TB,N,V_hasSetUpSizeConstraint"
- "_hasSetUpSizeConstraint"
- "activateConstraints:"
- "addSizeConstraint"
- "constraintWithItem:attribute:relatedBy:toItem:attribute:multiplier:constant:"
- "constraints"
- "findSizeLayoutConstraintIfExists"
- "firstAttribute"
- "firstItem"
- "hasSetUpSizeConstraint"
- "mainScreen"
- "scale"
- "secondItem"
- "setBackgroundColor:"
- "setConstant:"
- "setHasSetUpSizeConstraint:"
- "setUpHeightConstraintIfNecessary"
- "sizeLayoutAttribute"
- "tableSeparatorLightColor"
- "updateConstraints"
```
