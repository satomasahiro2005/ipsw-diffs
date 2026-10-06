## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/WritingToolsUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6bbb4` | `0x6c2d8` | **`+0x724`** |
| `__AUTH_CONST.__cfstring` | `0xe60` | `0xf80` | **`+0x120`** |
| `__TEXT.__cstring` | `0x3577` | `0x3647` | **`+0xd0`** |
| `__DATA_CONST.__objc_selrefs` | `0x3040` | `0x3098` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x4c04` | `0x4c3c` | **`+0x38`** |
| `__DATA_CONST.__const` | `0xdd8` | `0xe00` | **`+0x28`** |
| `__DATA_CONST.__objc_arraydata` | `0x48` | `0x70` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x8a0` | `0x8c8` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x6930` | `0x6950` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xa50` | `0xa70` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xe2c` | `0xe0c` | **`-0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x48` | `0x60` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1cb0` | `0x1cc8` | **`+0x18`** |
| `__TEXT.__const` | `0x3114` | `0x3124` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0xd60` | `0xd6c` | **`+0xc`** |
| `__TEXT.__swift5_fieldmd` | `0xcc0` | `0xcb4` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xf70` | `0xf78` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x3c` | `0x40` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x18` | `0x1c` | **`+0x4`** |

### Other Changes

```diff

-139.0.0.0.0
+143.0.0.0.0

-  Functions: 2994
-  Symbols:   3197
-  CStrings:  537
+  Functions: 2999
+  Symbols:   3205
+  CStrings:  546
Symbols:
+ -[WTUIAttributedStringController _attributedStringByRestoringInputStructureOnto:fromContext:]
+ -[WTUIAttributedStringController _attributedStringByRestoringTrailingNewlineOnto:fromContext:]
+ -[WTUIAttributedStringController _paragraphRangesInAttributedString:]
+ _NSParagraphStyleAttributeName
+ _NSPresentationIntentAttributeName
+ _OBJC_CLASS_$_NSCharacterSet
+ ___69-[WTUIAttributedStringController _paragraphRangesInAttributedString:]_block_invoke
+ ___block_descriptor_40_e8_32s_e52_v56?0"NSString"8{_NSRange=QQ}16{_NSRange=QQ}32^B48ls32l8
CStrings:
+ "TCListItemNumber"
+ "TCListLevelNumber"
+ "TCNoCopy"
+ "TCOrderedListItemNumber"
+ "TCParagraphNumber"
+ "TPItemNumber"
+ "TPMaxApproxItemNumber"
+ "TTPresentationAttributeNameOriginalForegroundColor"
+ "TTStyle"
+ "v56@?0@\"NSString\"8{_NSRange=QQ}16{_NSRange=QQ}32^B48"
- "DisableInvisibleTextWorkaround"
```
