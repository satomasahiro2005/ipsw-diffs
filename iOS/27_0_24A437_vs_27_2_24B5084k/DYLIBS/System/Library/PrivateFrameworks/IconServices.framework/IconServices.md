## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/IconServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x66928` | `0x674f0` | **`+0xbc8`** |
| `__TEXT.__oslogstring` | `0x3d2c` | `0x3f95` | **`+0x269`** |
| `__DATA_DIRTY.__bss` | `0x1c0` | `0x220` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x6934` | `0x6994` | **`+0x60`** |
| `__TEXT.__cstring` | `0x45e7` | `0x463a` | **`+0x53`** |
| `__AUTH_CONST.__objc_const` | `0x13f98` | `0x13fe8` | **`+0x50`** |
| `__DATA_CONST.__objc_selrefs` | `0x3180` | `0x31c8` | **`+0x48`** |
| `__DATA.__bss` | `0x698` | `0x660` | **`-0x38`** |
| `__DATA_CONST.__const` | `0xa50` | `0xa80` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x19e0` | `0x1a10` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x4a00` | `0x4a20` | **`+0x20`** |
| `__AUTH_CONST.__const` | `0x11a8` | `0x11c8` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x6d0` | `0x6d4` | **`+0x4`** |

### Other Changes

```diff

-792.102.0.0.0
+793.1.7.0.0

-  Functions: 2599
-  Symbols:   4962
-  CStrings:  1080
+  Functions: 2621
+  Symbols:   4983
+  CStrings:  1095
Symbols:
+ +[ISSymbol _keyPiecesToVariantOptions]
+ +[ISSymbol _orderedVariantOptions]
+ +[ISSymbol _variantOptionsToKeyPieces]
+ +[ISSymbol variantOptionsForKey:]
+ -[ISDefaults isInteriorDebugContentEnabled]
+ -[ISGenericRecipe allowsDebugBackground]
+ -[ISGenericRecipe debugBackgroundEnabled]
+ -[ISGenericRecipe setAllowsDebugBackground:]
+ -[ISGenericRecipe setDebugBackgroundEnabled:]
+ -[ISIconConfigurationMarkupParser symbolVariant]
+ _OBJC_IVAR_$_ISGenericRecipe._allowsDebugBackground
+ _OBJC_IVAR_$_ISGenericRecipe._debugBackgroundEnabled
+ __ISSymbolLog
+ __ISSymbolLog.log
+ __ISSymbolLog.onceToken
+ ___34+[ISSymbol _orderedVariantOptions]_block_invoke
+ ___38+[ISSymbol _keyPiecesToVariantOptions]_block_invoke
+ ___38+[ISSymbol _keyPiecesToVariantOptions]_block_invoke_2
+ ___38+[ISSymbol _variantOptionsToKeyPieces]_block_invoke
+ ____ISSymbolLog_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSNumber"8"NSString"16^B24ls32l8
+ __keyPiecesToVariantOptions.keyPiecesToOptions
+ __keyPiecesToVariantOptions.onceToken
+ __orderedVariantOptions.onceToken
+ __orderedVariantOptions.orderedOptions
+ __variantOptionsToKeyPieces.onceToken
+ __variantOptionsToKeyPieces.optionsToKeyPieces
+ _kISIconConfigurationKeySymbolVariant
- -[ISGenericRecipe isDebugModeEnabled]
- -[ISGenericRecipe setDebugModeEnabled:]
- _OBJC_IVAR_$_ISGenericRecipe._debugModeEnabled
- ___43+[ISSymbol _generateVariantKeyFromOptions:]_block_invoke
- __generateVariantKeyFromOptions:.onceToken
- __generateVariantKeyFromOptions:.optionsToKeyPieces
- __generateVariantKeyFromOptions:.orderedOptions
CStrings:
+ "20:34:20"
+ "Attempting to find symbol for type with id `%@` using strategy `%ld` and options `%llu`"
+ "Attempting to find symbol for type with id `%@`. Defaulting to default strategy and no options"
+ "Attempting to find symbol for type with id `%@`. Will use default strategy and no options"
+ "Attempting to find symbol for url: `%@`"
+ "Failed to find symbol for current device type %@. Error: %@"
+ "Found symbol `%@` for type `%@`"
+ "Found symbol `%@` for url `%@`"
+ "Found symbol name `%@` using bundleURL `%@` for url `%@`"
+ "Found type with id `%@` for url `%@`"
+ "ISSymbolVariant"
+ "Lookup for `%@` resolved to symbol name `%@` with url `%@`"
+ "Unknown variant option `%@`"
+ "interior_debug_content"
+ "symbols"
+ "v32@?0@\"NSNumber\"8@\"NSString\"16^B24"
- "16:00:27"
```
