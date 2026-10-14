## APTransport

> `/System/Library/PrivateFrameworks/APTransport.framework/APTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methlist` | `0x1d2c` | `0x1d64` | **`+0x38`** |
| `__TEXT.__text` | `0xb714c` | `0xb7180` | **`+0x34`** |
| `__AUTH_CONST.__objc_const` | `0x24f8` | `0x2518` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1bd8` | `0x1bf8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x30ebd` | `0x30ebf` | **`+0x2`** |

### Other Changes

```diff

-1005.12.1.0.0
+1005.13.1.1.0

-  Symbols:   4422
+  Symbols:   4423
Symbols:
+ _APSIsHomeAccessory
Functions:
~ __APBonjourBrowserSetModeInternal : 1980 -> 2000
~ -[APBrowserBTLEManager update] : 340 -> 348
~ +[APBonjourCacheHomeKit isDeviceCacheable:] : 212 -> 228
~ __APBonjourBrowserTickleDetailedMode : 744 -> 752
CStrings:
+ "1005.13.1.1"
- "1005.12.1"
```
