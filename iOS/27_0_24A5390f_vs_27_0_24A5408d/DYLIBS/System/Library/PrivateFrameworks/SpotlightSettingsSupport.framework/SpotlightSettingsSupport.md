## SpotlightSettingsSupport

> `/System/Library/PrivateFrameworks/SpotlightSettingsSupport.framework/SpotlightSettingsSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x498c` | `0x5a30` | **`+0x10a4`** |
| `__DATA_CONST.__objc_selrefs` | `0x3f0` | `0x5a0` | **`+0x1b0`** |
| `__AUTH_CONST.__cfstring` | `0x880` | `0xa00` | **`+0x180`** |
| `__TEXT.__cstring` | `0x7c4` | `0x8c7` | **`+0x103`** |
| `__AUTH_CONST.__objc_const` | `0x578` | `0x648` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x2cc` | `0x37c` | **`+0xb0`** |
| `__AUTH_CONST.__objc_intobj` | `—` | `0x78` | **`+0x78`** |
| `__AUTH.__objc_data` | `0xf0` | `0x140` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x248` | `0x298` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x1e8` | `0x228` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x5a` | `0x9a` | **`+0x40`** |
| `__AUTH_CONST.__objc_arrayobj` | `—` | `0x30` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x190` | `0x1c0` | **`+0x30`** |
| `__AUTH_CONST.__const` | `0x60` | `0x80` | **`+0x20`** |
| `__DATA_CONST.__objc_arraydata` | `—` | `0x20` | **`+0x20`** |
| `__DATA_CONST.__objc_classlist` | `0x30` | `0x38` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__const` | `0x70` | `0x78` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x40` | `0x44` | **`+0x4`** |

### Other Changes

```diff

-236.0.11.100.0
+236.0.21.100.0

-  Functions: 81
-  Symbols:   298
-  CStrings:  87
+  Functions: 97
+  Symbols:   336
+  CStrings:  103
Symbols:
+ -[SpotlightPopUpMenuCell .cxx_destruct]
+ -[SpotlightPopUpMenuCell initWithStyle:reuseIdentifier:specifier:]
+ -[SpotlightPopUpMenuCell popUpButton]
+ -[SpotlightPopUpMenuCell refreshCellContentsWithSpecifier:]
+ -[SpotlightPopUpMenuCell setPopUpButton:]
+ -[SpotlightPopUpMenuCell setUpPopUpButton]
+ -[SpotlightSettingsController isShowAppShortcutsEnabled]
+ -[SpotlightSettingsController isSuggestAppsDisabled]
+ -[SpotlightSettingsController isSuggestAppsExpanded]
+ -[SpotlightSettingsController setShowAppShortcutsEnabled:]
+ -[SpotlightSettingsController setSuggestAppsCount:forSpecifier:]
+ -[SpotlightSettingsController suggestAppsCountForSpecifier:]
+ -[SpotlightSettingsController suggestAppsCountOptions]
+ -[SpotlightSettingsController tableView:shouldHighlightRowAtIndexPath:]
+ GCC_except_table8
+ _OBJC_CLASS_$_NSConstantArray
+ _OBJC_CLASS_$_NSConstantIntegerNumber
+ _OBJC_CLASS_$_NSLayoutConstraint
+ _OBJC_CLASS_$_SpotlightPopUpMenuCell
+ _OBJC_CLASS_$_UIAction
+ _OBJC_CLASS_$_UIButton
+ _OBJC_CLASS_$_UIButtonConfiguration
+ _OBJC_CLASS_$_UIColor
+ _OBJC_CLASS_$_UIDevice
+ _OBJC_CLASS_$_UIMenu
+ _OBJC_IVAR_$_SpotlightPopUpMenuCell._popUpButton
+ _OBJC_METACLASS_$_SpotlightPopUpMenuCell
+ _SpotlightSettingsZKWExpandedKey
+ __OBJC_$_INSTANCE_METHODS_SpotlightPopUpMenuCell
+ __OBJC_$_INSTANCE_VARIABLES_SpotlightPopUpMenuCell
+ __OBJC_$_PROP_LIST_SpotlightPopUpMenuCell
+ __OBJC_CLASS_RO_$_SpotlightPopUpMenuCell
+ __OBJC_METACLASS_RO_$_SpotlightPopUpMenuCell
+ ___42-[SpotlightPopUpMenuCell setUpPopUpButton]_block_invoke
+ ___59-[SpotlightPopUpMenuCell refreshCellContentsWithSpecifier:]_block_invoke
+ ___block_descriptor_32_e18_v16?0"UIAction"8l
+ ___block_descriptor_48_e8_32s40s_e18_v16?0"UIAction"8ls32l8s40l8
+ _objc_retain_x28
CStrings:
+ " "
+ "BEFORE_SEARCHING_GROUP"
+ "Don't Suggest"
+ "OFF"
+ "ON"
+ "SEARCH_AND_LOOKUP_SHOW_RECENT_SEARCHES"
+ "SUGGEST_APPS"
+ "SUGGEST_APPS_COUNT_FORMAT"
+ "SUGGEST_APPS_DONT_SUGGEST"
+ "SUGGEST_APPS_SHORTCUTS"
+ "SpotlightZKWExpanded"
+ "Suggest Apps: selected %{public}@ -> ZKW suggestions %{public}@"
+ "SuggestionsSpotlightAppShortcutsEnabled"
+ "SuggestionsSpotlightZKWEnabled"
+ "i"
+ "q"
+ "v16@?0@\"UIAction\"8"
- "SEARCH_AND_LOOKUP_SHOW_RECENTS"
```
