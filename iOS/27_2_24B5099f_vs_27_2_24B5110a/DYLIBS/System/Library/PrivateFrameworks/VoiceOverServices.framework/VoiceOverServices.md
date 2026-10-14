## VoiceOverServices

> `/System/Library/PrivateFrameworks/VoiceOverServices.framework/VoiceOverServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x35a28` | `0x36a0c` | **`+0xfe4`** |
| `__TEXT.__oslogstring` | `0x4f4` | `0x5a8` | **`+0xb4`** |
| `__TEXT.__objc_methlist` | `0x2fc4` | `0x301c` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x4490` | `0x44e0` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0x9300` | `0x9340` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x3cc0` | `0x3d00` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x2240` | `0x2278` | **`+0x38`** |
| `__DATA.__bss` | `0x9a8` | `0x9d0` | **`+0x28`** |
| `__TEXT.__cstring` | `0x76a6` | `0x76c8` | **`+0x22`** |
| `__TEXT.__const` | `0x80` | `0x90` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x778` | `0x788` | **`+0x10`** |
| `__DATA_DIRTY.__bss` | `0x1368` | `0x1360` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x130` | `0x134` | **`+0x4`** |

### Other Changes

```diff

-3245.8.4.2.0
+3245.8.9.0.0

-  Functions: 1500
-  Symbols:   3376
-  CStrings:  1242
+  Functions: 1509
+  Symbols:   3390
+  CStrings:  1248
Symbols:
+ +[VOSCommand BraillePanPageDown]
+ +[VOSCommand BraillePanPageUp]
+ -[VOSCommandProfile _coalesceDuplicateProfileCommands]
+ -[VOSCommandProfile _isUnboundProfileCommand:]
+ -[VOSCommandProfile _releaseGesturesShadowedByUnboundCommands]
+ -[VOSCommandProfile requiresResave]
+ -[_VOSProfileMode removeCommand:]
+ GCC_except_table1285
+ GCC_except_table1351
+ GCC_except_table1359
+ GCC_except_table1479
+ GCC_except_table1485
+ _BraillePanPageDown._Command
+ _BraillePanPageDown.onceToken
+ _BraillePanPageUp._Command
+ _BraillePanPageUp.onceToken
+ _OBJC_IVAR_$_VOSCommandProfile._requiresResave
+ ___30+[VOSCommand BraillePanPageUp]_block_invoke
+ ___32+[VOSCommand BraillePanPageDown]_block_invoke
+ _kVOTEventCommandBraillePanPageDown
+ _kVOTEventCommandBraillePanPageUp
- GCC_except_table1280
- GCC_except_table1346
- GCC_except_table1354
- GCC_except_table1470
- GCC_except_table1476
- _kVOTEventCommandBraillePlanarPanLeft
- _kVOTEventCommandBraillePlanarPanRight
CStrings:
+ "!"
+ "BraillePanPageDown"
+ "BraillePanPageUp"
+ "Coalesced %lu duplicate profile command(s) in mode %@"
+ "Gesture %@ is claimed by more than one command in mode %@. Leaving it alone"
+ "Released %lu gesture(s) shadowed by %@ in mode %@"
+ "VOTEventCommandBraillePanPageDown"
+ "VOTEventCommandBraillePanPageUp"
- "VOTEventCommandBraillePlanarPanLeft"
- "VOTEventCommandBraillePlanarPanRight"
```
