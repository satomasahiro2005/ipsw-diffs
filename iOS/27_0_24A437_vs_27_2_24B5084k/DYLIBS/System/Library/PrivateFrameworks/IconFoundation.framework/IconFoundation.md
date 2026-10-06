## IconFoundation

> `/System/Library/PrivateFrameworks/IconFoundation.framework/IconFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39ba4` | `0x39e18` | **`+0x274`** |
| `__TEXT.__objc_methlist` | `0x3164` | `0x31b4` | **`+0x50`** |
| `__TEXT.__cstring` | `0x12d0e` | `0x12cd8` | **`-0x36`** |
| `__AUTH_CONST.__objc_const` | `0x4e08` | `0x4e38` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x1ba0` | `0x1b80` | **`-0x20`** |
| `__AUTH_CONST.__const` | `0x8c8` | `0x8a8` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x3d0` | `0x3c8` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1f40` | `0x1f48` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xf38` | `0xf40` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x348` | `0x34c` | **`+0x4`** |

### Other Changes

```diff

-792.102.0.0.0
+793.1.7.0.0

-  Functions: 1548
-  Symbols:   2558
-  CStrings:  2892
+  Functions: 1553
+  Symbols:   2564
+  CStrings:  2890
Symbols:
+ +[IFGraphicSymbolOverrides _parseItems]
+ +[IFGraphicSymbolOverrides sharedOverrides]
+ -[IFGraphicSymbolOverride hash]
+ -[IFGraphicSymbolOverride isEqual:]
+ -[IFGraphicSymbolOverrides flush]
+ -[IFGraphicSymbolOverrides init]
+ -[IFGraphicSymbolOverrides lock]
+ -[IFGraphicSymbolOverrides setLock:]
+ _OBJC_IVAR_$_IFGraphicSymbolOverrides._lock
+ ___43+[IFGraphicSymbolOverrides sharedOverrides]_block_invoke
+ _sharedOverrides.onceToken
+ _sharedOverrides.shared
- +[IFGraphicSymbolOverrides overrides]
- -[IFGraphicSymbolOverrides setItems:]
- _OBJC_CLASS_$_NSCache
- ___37+[IFGraphicSymbolOverrides overrides]_block_invoke
- _overrides.cache
- _overrides.onceToken
CStrings:
- "_ReadFreeList: tring to read count of freelist table."
- "overrides"
```
