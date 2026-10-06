## Music

> `/System/Library/AccessibilityBundles/Music.axbundle/Music`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__objc_const` | `0x3290` | `0x3250` | **`-0x40`** |
| `__AUTH_CONST.__cfstring` | `0x3600` | `0x3620` | **`+0x20`** |
| `__TEXT.__cstring` | `0x29b0` | `0x2998` | **`-0x18`** |
| `__TEXT.__text` | `0xbecc` | `0xbedc` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x7c0` | `0x7c8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x4` | `—` | **`-0x4`** |

### Other Changes

```diff

-3036.2.0.0.0
+3039.1.0.0.0

-  Symbols:   1013
-  CStrings:  486
+  Symbols:   1011
+  CStrings:  484
Symbols:
+ ___SymbolButtonAccessibility__accessibilityIsInCell
- _OBJC_IVAR_$_SymbolButtonAccessibility._accessibilityIsInCell
- __OBJC_$_INSTANCE_VARIABLES_SymbolButtonAccessibility
- __OBJC_$_PROP_LIST_SymbolButtonAccessibility
CStrings:
+ "accessibilityRepeatAvailable"
+ "accessibilityShuffleAvailable"
- "Optional<AttributedString>"
- "Optional<MPRepeatType>"
- "Optional<MPShuffleType>"
- "subtitle"
```
