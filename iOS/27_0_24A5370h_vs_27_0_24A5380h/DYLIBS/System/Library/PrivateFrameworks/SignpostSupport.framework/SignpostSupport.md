## SignpostSupport

> `/System/Library/PrivateFrameworks/SignpostSupport.framework/SignpostSupport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x16d0` | `0x1db0` | **`+0x6e0`** |
| `__DATA_DIRTY.__objc_data` | `0x1d10` | `0x1630` | **`-0x6e0`** |
| `__TEXT.__text` | `0x77508` | `0x775a4` | **`+0x9c`** |
| `__AUTH_CONST.__cfstring` | `0x1caa0` | `0x1cac0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1a756` | `0x1a775` | **`+0x1f`** |
| `__DATA.__data` | `0x1178` | `0x1180` | **`+0x8`** |

### Other Changes

```diff

-200.0.0.0.0
+201.0.0.0.0

-  Symbols:   7305
-  CStrings:  3922
+  Symbols:   7306
+  CStrings:  3923
Symbols:
+ _kSSCAMetalLayerClientSessionCAKey_OnGlassIntervalSumOfSquaresMs2
Functions:
~ +[SignpostEvent _nameStringFromFormatPrefix:] : 324 -> 304
~ -[SSCAMetalLayerClientSession coreAnalyticsEvent] : 3472 -> 3648
CStrings:
+ "OnGlassIntervalSumOfSquaresMs2"
```
