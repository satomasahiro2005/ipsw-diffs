## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReaderOutput.framework/ScreenReaderOutput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9dcb8` | `0x9e25c` | **`+0x5a4`** |
| `__AUTH_CONST.__objc_const` | `0xbd48` | `0xbda0` | **`+0x58`** |
| `__TEXT.__objc_methlist` | `0x9208` | `0x9248` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x5740` | `0x5720` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x4858` | `0x4878` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x194c` | `0x1964` | **`+0x18`** |
| `__TEXT.__cstring` | `0x5c0c` | `0x5bf5` | **`-0x17`** |
| `__TEXT.__const` | `0x183c` | `0x184c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x8d4` | `0x8dc` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2900` | `0x2908` | **`+0x8`** |

### Other Changes

```diff

-467.3.1.0.0
+467.3.3.0.0

-  Functions: 4011
-  Symbols:   5813
-  CStrings:  1081
+  Functions: 4015
+  Symbols:   5820
+  CStrings:  1080
Symbols:
+ -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROMobileBrailleDisplayInputManager _storedUserDefaultsForModelIdentifier:]
+ -[SCROMobileBrailleDisplayInputManager _userDefaultsForDisplayWithToken:]
+ -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:productName:driverIdentifier:]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject modelIdentifierForPlist]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject setModelIdentifierForPlist:]
+ GCC_except_table2931
+ GCC_except_table2947
+ GCC_except_table2966
+ GCC_except_table2967
+ GCC_except_table2968
+ GCC_except_table3033
+ GCC_except_table3035
+ GCC_except_table3038
+ GCC_except_table3040
+ OBJC_IVAR_$_SCROBrailleDisplay._driverModelIdentifierForAnalytics
+ _OBJC_IVAR_$_SCROMobileBrailleDisplayInputManagerCacheObject._modelIdentifierForPlist
+ ___95-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___96-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8ls32l8s40l8s48l8s56l8s64l8
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8
+ _kSCROBrailleDisplayModelIdentifierForAnalytics
- -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:]
- GCC_except_table2927
- GCC_except_table2943
- GCC_except_table2962
- GCC_except_table2963
- GCC_except_table2964
- GCC_except_table3027
- GCC_except_table3029
- GCC_except_table3032
- GCC_except_table3034
- ___82-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]_block_invoke
- ___83-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8ls32l8s40l8s48l8s56l8
- ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8
CStrings:
+ "BrailleDisplayModelIdentifierForAnalytics"
- "NLS eReader Humanware"
- "com.apple.scrod.braille.driver.nls.ereader"
```
