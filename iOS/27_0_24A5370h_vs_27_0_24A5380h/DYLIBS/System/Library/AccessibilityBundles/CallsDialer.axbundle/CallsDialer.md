## CallsDialer

> `/System/Library/AccessibilityBundles/CallsDialer.axbundle/CallsDialer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x690` | `—` | **`-0x690`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x690` | **`+0x690`** |
| `__DATA.__bss` | `0x20` | `0x8` | **`-0x18`** |
| `__DATA_DIRTY.__bss` | `—` | `0x18` | **`+0x18`** |
| `__TEXT.__cstring` | `0x959` | `0x962` | **`+0x9`** |
| `__TEXT.__text` | `0x2d7c` | `0x2d80` | **`+0x4`** |

### Other Changes

```diff

-3039.1.0.0.0
+3042.0.0.0.0
Symbols:
+ -[PHHandsetDialerLCDViewAccessibility initWithFrame:forDialerType:appType:enableSmartDialer:enableSmartDialerExpandedSearch:delegate:]
- -[PHHandsetDialerLCDViewAccessibility initWithFrame:forDialerType:appType:enableSmartDialer:enableSmartDialerExpandedSearch:]
CStrings:
+ "initWithFrame:forDialerType:appType:enableSmartDialer:enableSmartDialerExpandedSearch:delegate:"
- "initWithFrame:forDialerType:appType:enableSmartDialer:enableSmartDialerExpandedSearch:"
```
