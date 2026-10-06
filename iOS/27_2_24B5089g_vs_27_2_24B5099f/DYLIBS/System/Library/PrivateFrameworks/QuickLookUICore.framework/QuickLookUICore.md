## QuickLookUICore

> `/System/Library/PrivateFrameworks/QuickLookUICore.framework/QuickLookUICore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21418` | `0x21588` | **`+0x170`** |
| `__AUTH_CONST.__objc_const` | `0x7628` | `0x7688` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x314c` | `0x317c` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2020` | `0x2040` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x850` | `0x868` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1ffe` | `0x2011` | **`+0x13`** |
| `__DATA_CONST.__objc_selrefs` | `0x2100` | `0x2110` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x3a8` | `0x3b0` | **`+0x8`** |

### Other Changes

```diff

-1034.1.3.0.0
+1034.1.4.0.0

-  Functions: 1030
-  Symbols:   2149
-  CStrings:  409
+  Functions: 1034
+  Symbols:   2155
+  CStrings:  410
Symbols:
+ -[QLItem canEnterFullScreen]
+ -[QLItem setCanEnterFullScreen:]
+ -[QLPreviewContext canEnterFullScreen]
+ -[QLPreviewContext setCanEnterFullScreen:]
+ _OBJC_IVAR_$_QLItem._canEnterFullScreen
+ _OBJC_IVAR_$_QLPreviewContext._canEnterFullScreen
Functions:
~ -[QLItem _commonInit] : 16 -> 20
~ -[QLItem internalCopy] : 576 -> 588
~ -[QLItem encodeWithCoder:] : 1656 -> 1684
~ -[QLItem initWithCoder:] : 1352 -> 1400
~ -[QLItem createPreviewContext] : 588 -> 608
- -[QLItem setInternalShouldCreateTemporaryDirectoryInHost:]
+ -[QLItem setInternalShouldCreateTemporaryDirectoryInHost:]
- -[QLItem setSandboxingURLWrapper:]
+ -[QLItem setClientPreviewItemDisplayState:]
+ -[QLItem generatedItemContentType]
+ -[QLItem setGeneratedReplyType:]
~ -[QLItem(PreviewInfo) _uncachedPreviewItemTypeForContentType:] : 664 -> 780
~ -[QLPreviewContext isEqual:] : 972 -> 1000
~ -[QLPreviewContext encodeWithCoder:] : 988 -> 1016
~ -[QLPreviewContext initWithCoder:] : 840 -> 888
+ -[QLPreviewContext shouldPreventMachineReadableCodeDetection]
+ -[QLPreviewContext setEditedFileBehavior:]
CStrings:
+ "canEnterFullScreen"
```
