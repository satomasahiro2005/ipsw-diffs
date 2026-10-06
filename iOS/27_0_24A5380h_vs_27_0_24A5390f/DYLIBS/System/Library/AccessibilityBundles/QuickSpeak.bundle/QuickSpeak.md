## QuickSpeak

> `/System/Library/AccessibilityBundles/QuickSpeak.bundle/QuickSpeak`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xf80` | `0xe80` | **`-0x100`** |
| `__TEXT.__text` | `0x92ec` | `0x920c` | **`-0xe0`** |
| `__TEXT.__cstring` | `0xdbd` | `0xd23` | **`-0x9a`** |
| `__AUTH_CONST.__objc_const` | `0x1850` | `0x1870` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xf94` | `0xfac` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0xd28` | `0xd38` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2c8` | `0x2c0` | **`-0x8`** |

### Other Changes

```diff

-3234.5.0.0.0
+3237.1.0.0.0

-  CStrings:  163
+  CStrings:  152
Functions:
~ ___20-[AXQuickSpeak init]_block_invoke : 540 -> 316
CStrings:
- ":"
- "NSArray"
- "NSMutableArray"
- "UICalloutBarButton"
- "_targetForAction:"
- "buttonPressed:"
- "delegate"
- "m_currentSystemButtons"
- "m_extraItems"
- "setPage:"
- "updateAvailableButtons"
```
