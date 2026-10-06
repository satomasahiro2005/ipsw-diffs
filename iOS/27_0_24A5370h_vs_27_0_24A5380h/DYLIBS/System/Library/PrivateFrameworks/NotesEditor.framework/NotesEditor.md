## NotesEditor

> `/System/Library/PrivateFrameworks/NotesEditor.framework/NotesEditor`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3075f4` | `0x307f00` | **`+0x90c`** |
| `__DATA.__bss` | `0x5468` | `0x5268` | **`-0x200`** |
| `__DATA_DIRTY.__bss` | `0x1d10` | `0x1f10` | **`+0x200`** |
| `__DATA_DIRTY.__data` | `0x1168` | `0x1238` | **`+0xd0`** |
| `__DATA_DIRTY.__objc_data` | `0x4110` | `0x41e0` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x5628` | `0x5560` | **`-0xc8`** |
| `__TEXT.__gcc_except_tab` | `0x3cd8` | `0x3d48` | **`+0x70`** |
| `__DATA.__data` | `0x881c` | `0x87bc` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x6220` | `0x61e0` | **`-0x40`** |
| `__AUTH_CONST.__objc_const` | `0x20678` | `0x206b8` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x5015` | `0x5055` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x30c0` | `0x30f8` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0x56c0` | `0x56f8` | **`+0x38`** |
| `__AUTH.__data` | `0x2cd0` | `0x2ca0` | **`-0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xf960` | `0xf988` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x3988` | `0x39ac` | **`+0x24`** |
| `__TEXT.__swift5_typeref` | `0x36184` | `0x361a8` | **`+0x24`** |
| `__TEXT.__oslogstring` | `0x6f1c` | `0x6f3c` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x9fb8` | `0x9fd0` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x3980` | `0x3970` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0xb7f0` | `0xb800` | **`+0x10`** |
| `__TEXT.__const` | `0xbc74` | `0xbc84` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x16b6c` | `0x16b7c` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x3480` | `0x3490` | **`+0x10`** |
| `__DATA.__common` | `0x1a8` | `0x1a0` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x1b0` | `0x1b8` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2991.0.0.0.0
+2996.0.0.0.0

-  Functions: 15671
-  Symbols:   14280
-  CStrings:  1904
+  Functions: 15681
+  Symbols:   14287
+  CStrings:  1903
Symbols:
+ -[ICNoteEditorNavigationItemConfiguration contentSizeCategoryDidChange]
+ GCC_except_table60
+ GCC_except_table86
+ GCC_except_table93
+ GCC_except_table97
+ _ICTextViewSectionLinkFractionalOffset
+ _OBJC_CLASS_$_UIFontMetrics
+ _UIBarButtonItemVisibilityPriorityHigh
+ ___block_descriptor_34_e14_v16?0?<v?>8l
+ ___block_descriptor_42_e8_32bs_e17_v16?0"NSError"8ls32l8
+ ___swift_memcpy160_8
+ _kICReindexAttachmentsOnLaunchKey
+ _symbolic So17UITraitCollectionCSg
+ _symbolic _____SgXw 11NotesEditor06ICNoteB28ContextualInputAccessoryViewC
- GCC_except_table85
- GCC_except_table88
- GCC_except_table92
- __UIBarElementVisibilityPriorityHigh
- ___block_descriptor_32_e14_v16?0?<v?>8l
- ___block_descriptor_40_e8_32bs_e17_v16?0"NSError"8ls32l8
- ___swift_memcpy152_8
CStrings:
+ "Add Link (Link Editor header)"
+ "Add Link (menu item)"
+ "App failed to reindex the search index. Will try again on next open"
+ "App needs to reindex the search index (everything: %@, deferred attachments: %@)"
- "App failed to clean up the search index. Will try again on next open"
- "App needs to clean up the search index"
- "Double tap to open the Writing Tools popover."
- "Use Writing Tools"
- "Writing Tools"
```
