## SettingsCellular

> `/System/Library/PrivateFrameworks/SettingsCellular.framework/SettingsCellular`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa700` | `0xa964` | **`+0x264`** |
| `__TEXT.__oslogstring` | `0x9eb` | `0xa86` | **`+0x9b`** |
| `__AUTH_CONST.__objc_const` | `0x1638` | `0x1668` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0xeac` | `0xedc` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0xbc0` | `0xbe8` | **`+0x28`** |
| `__DATA.__objc_ivar` | `0x68` | `0x6c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  Functions: 250
-  Symbols:   634
-  CStrings:  149
+  Functions: 254
+  Symbols:   639
+  CStrings:  152
Symbols:
+ -[PSSimStatusCache fetchSupportsDynamicSIMConfigurationIfNeeded]
+ -[PSSimStatusCache setSupportsDynamicSIMConfigurationCache:]
+ -[PSSimStatusCache supportsDynamicSIMConfigurationCache]
+ -[PSSimStatusCache supportsDynamicSIMConfiguration]
+ _OBJC_IVAR_$_PSSimStatusCache._supportsDynamicSIMConfigurationCache
CStrings:
+ "Failed to fetch dynamic SIM configuration capability: %@"
+ "Fetch succeeded: supportsDynamicSIMConfiguration=%@"
+ "Fetching dynamic SIM configuration capability"
```
