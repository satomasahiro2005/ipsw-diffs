## HDSDiagnostics

> `/Applications/HDSViewService.app/PlugIns/HDSDiagnostics.appex/HDSDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbe4` | `0xcac` | **`+0xc8`** |
| `__DATA_CONST.__cfstring` | `0x140` | `0x1a0` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x340` | `0x3a0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x115` | `0x174` | **`+0x5f`** |
| `__TEXT.__oslogstring` | `0xb5` | `0x10f` | **`+0x5a`** |
| `__TEXT.__objc_methname` | `0x2a4` | `0x2d8` | **`+0x34`** |
| `__DATA.__objc_selrefs` | `0xe8` | `0x100` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xe0` | `0xe8` | **`+0x8`** |
| `__TEXT.__const` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x88` | `0x90` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-405.0.11.0.0
+405.10.26.0.0

-  Symbols:   49
-  CStrings:  57
+  Symbols:   50
+  CStrings:  64
Symbols:
+ _objc_retain_x2
Functions:
~ sub_1000011b8 : 244 -> 444
CStrings:
+ "Consent not provided for sensitive attachment collection; skipping. Host app [%{public}@]"
+ "DEExtensionAttachmentsParamConsentProvidedKey"
+ "DEExtensionHostAppKey"
+ "boolValue"
+ "com.apple.enhancedloggingd"
+ "isEqualToString:"
+ "objectForKeyedSubscript:"
```
