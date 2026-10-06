## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/PhotosUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42370` | `0x42e50` | **`+0xae0`** |
| `__AUTH_CONST.__objc_const` | `0x6e38` | `0x6f48` | **`+0x110`** |
| `__AUTH.__objc_data` | `0x1fd8` | `0x20a8` | **`+0xd0`** |
| `__TEXT.__objc_methlist` | `0x3db4` | `0x3e64` | **`+0xb0`** |
| `__TEXT.__cstring` | `0x4bcb` | `0x4c64` | **`+0x99`** |
| `__TEXT.__constg_swiftt` | `0xd20` | `0xd64` | **`+0x44`** |
| `__TEXT.__const` | `0x2f78` | `0x2fb8` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x1928` | `0x1968` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x20e8` | `0x2120` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xbb2` | `0xbea` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0xbd8` | `0xc0c` | **`+0x34`** |
| `__AUTH.__data` | `0x678` | `0x6a8` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2220` | `0x2240` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xb21` | `0xb41` | **`+0x20`** |
| `__DATA.__data` | `0x1ae8` | `0x1af8` | **`+0x10`** |
| `__DATA_CONST.__const` | `0xd60` | `0xd70` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x610` | `0x618` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x220` | `0x228` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x118` | `0x11c` | **`+0x4`** |

### Other Changes

```diff

-910.33.102.0.0
+912.0.111.0.0

-  Functions: 2953
-  Symbols:   2909
-  CStrings:  552
+  Functions: 2994
+  Symbols:   2926
+  CStrings:  557
Symbols:
+ +[_PHPickerSuggestionGroup customSuggestionGroupWithItemIdentifiers:]
+ -[PHPickerSearchText initWithPhotoSearchSuggestion:]
+ GCC_except_table864
+ GCC_except_table874
+ GCC_except_table879
+ GCC_except_table958
+ _OBJC_CLASS_$_PHSearchUtility
+ _OBJC_CLASS_$_PUPickerCustomItemIdentifiersSuggestion
+ _OBJC_METACLASS_$_PUPickerCustomItemIdentifiersSuggestion
+ _OUTLINED_FUNCTION_91
+ __CLASS_METHODS_PUPickerCustomItemIdentifiersSuggestion
+ __CLASS_PROPERTIES_PUPickerCustomItemIdentifiersSuggestion
+ __DATA_PUPickerCustomItemIdentifiersSuggestion
+ __INSTANCE_METHODS_PUPickerCustomItemIdentifiersSuggestion
+ __IVARS_PUPickerCustomItemIdentifiersSuggestion
+ __METACLASS_DATA_PUPickerCustomItemIdentifiersSuggestion
+ __PROPERTIES_PUPickerCustomItemIdentifiersSuggestion
+ __PROTOCOLS_PUPickerCustomItemIdentifiersSuggestion
+ _symbolic So27PHSharedAlbumCreationResultCSg
+ _symbolic So7NSErrorCSg
+ _symbolic _____ 8PhotosUI37PickerCustomItemIdentifiersSuggestionC
- GCC_except_table862
- GCC_except_table872
- GCC_except_table875
- GCC_except_table956
CStrings:
+ " "
+ "-[PHPickerSearchText initWithPhotoSearchSuggestion:]"
+ "PhotosUI.PickerCustomItemIdentifiersSuggestion"
+ "itemIdentifiersKey"
+ "suggestion != nil"
```
