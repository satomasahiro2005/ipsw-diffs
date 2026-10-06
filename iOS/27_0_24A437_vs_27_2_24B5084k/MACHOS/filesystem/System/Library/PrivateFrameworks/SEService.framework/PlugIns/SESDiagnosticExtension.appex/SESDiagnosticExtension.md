## SESDiagnosticExtension

> `/System/Library/PrivateFrameworks/SEService.framework/PlugIns/SESDiagnosticExtension.appex/SESDiagnosticExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa70` | `0xae0` | **`+0x70`** |
| `__TEXT.__cstring` | `0x188` | `0x1b6` | **`+0x2e`** |
| `__TEXT.__oslogstring` | `0x1bd` | `0x1e4` | **`+0x27`** |
| `__DATA_CONST.__cfstring` | `0x2e0` | `0x300` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3e0` | `0x400` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x308` | `0x312` | **`+0xa`** |
| `__DATA.__objc_selrefs` | `0x110` | `0x118` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-70.39.1.0.0
+71.7.0.0.0

-  CStrings:  70
+  CStrings:  73
Functions:
~ sub_100001318 : 784 -> 896
CStrings:
+ "DEExtensionAttachmentsParamConsentProvidedKey"
+ "SESDiagnosticExtension: consent denied"
+ "boolValue"
```
