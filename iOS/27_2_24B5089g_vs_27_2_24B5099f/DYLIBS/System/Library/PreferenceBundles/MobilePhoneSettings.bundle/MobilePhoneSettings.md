## MobilePhoneSettings

> `/System/Library/PreferenceBundles/MobilePhoneSettings.bundle/MobilePhoneSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8cd0` | `0x8e08` | **`+0x138`** |
| `__AUTH_CONST.__cfstring` | `0x900` | `0x920` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb08` | `0xb20` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xaa8` | `0xac0` | **`+0x18`** |
| `__TEXT.__cstring` | `0xcd8` | `0xce8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x2b0` | `0x2b8` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0xdc` | `0xe0` | **`+0x4`** |

### Other Changes

```diff

-3077.200.64.2.3
+3077.200.88.0.0

-  Functions: 243
-  Symbols:   663
-  CStrings:  112
+  Functions: 245
+  Symbols:   666
+  CStrings:  113
Symbols:
+ -[PHSettingsRootListController isSimulatedModeEnabled:]
+ -[PHSettingsRootListController setSimulatedModeEnabled:specifier:]
+ _TUSimulatedModeEnabledKey
CStrings:
+ "Simulated Mode"
```
