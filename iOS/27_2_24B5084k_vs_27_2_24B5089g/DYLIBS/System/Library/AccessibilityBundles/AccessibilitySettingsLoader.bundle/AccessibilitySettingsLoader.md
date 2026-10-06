## AccessibilitySettingsLoader

> `/System/Library/AccessibilityBundles/AccessibilitySettingsLoader.bundle/AccessibilitySettingsLoader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x113b0` | `0x113fc` | **`+0x4c`** |
| `__TEXT.__oslogstring` | `0x613` | `0x651` | **`+0x3e`** |
| `__DATA.__bss` | `0x2a0` | `0x270` | **`-0x30`** |
| `__DATA_DIRTY.__bss` | `0x100` | `0x130` | **`+0x30`** |

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  CStrings:  323
+  CStrings:  324
Functions:
~ -[GuidedAccessManager loadRequiredBundlesForUnmanagedASAM] : 276 -> 352
CStrings:
+ "Loading GAX bundles and pinging BackBoard for unmanaged ASAM."
```
