## UIFoundation

> `/System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10a748` | `0x10a8d0` | **`+0x188`** |
| `__AUTH.__objc_data` | `0x1310` | `0x1220` | **`-0xf0`** |
| `__DATA_DIRTY.__objc_data` | `0x1a40` | `0x1b30` | **`+0xf0`** |
| `__AUTH_CONST.__objc_const` | `0x12bd8` | `0x12bf8` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xbbbc` | `0xbbd4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x6900` | `0x6910` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x81` | `0x79` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x1320` | `0x1324` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x35b4` | `0x35b8` | **`+0x4`** |

### Other Changes

```diff

-1057.1.0.0.0
+1057.3.0.0.0

-  Functions: 5367
-  Symbols:   9375
+  Functions: 5369
+  Symbols:   9377
Symbols:
+ -[NSCoreTypesetter _createLayoutLineFragmentStartingWithCharacterIndex:proposedLineFragmentRect:baseLineRef:range:paragraphStyle:paragraphArbitrator:lineBreakMode:hasAttachments:enforcesMinimumLine:lineFragmentRect:glyphOrigin:hyphenated:forcedClusterBreak:]
+ -[NSCoreTypesetter _minimumLineFragmentRectForProposedRect:atIndex:writingDirection:]
+ -[NSTextContainer _serialNumber]
+ _OBJC_IVAR_$_NSTextContainer._serialNumber
+ _OBJC_IVAR_$_NSTextLayoutFragment._textContainerSerialNumberForAnchoredAttachmentViewProviderCache
+ __commonInit.__NSTextContainerSerialNumberSource
- -[NSCoreTypesetter _createLayoutLineFragmentStartingWithCharacterIndex:proposedLineFragmentRect:baseLineRef:range:paragraphStyle:paragraphArbitrator:lineBreakMode:hasAttachments:lineFragmentRect:glyphOrigin:hyphenated:forcedClusterBreak:]
- GCC_except_table39
- GCC_except_table51
- _OBJC_IVAR_$_NSTextLayoutFragment._textContainerForAnchoredAttachmentViewProviderCache
```
