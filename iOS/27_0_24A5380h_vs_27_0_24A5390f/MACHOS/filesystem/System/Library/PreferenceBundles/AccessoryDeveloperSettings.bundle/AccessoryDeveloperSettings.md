## AccessoryDeveloperSettings

> `/System/Library/PreferenceBundles/AccessoryDeveloperSettings.bundle/AccessoryDeveloperSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0xab0` | `0x9f5` | **`-0xbb`** |
| `__TEXT.__text` | `0x38a8` | `0x3840` | **`-0x68`** |
| `__DATA_CONST.__cfstring` | `0xce0` | `0xc80` | **`-0x60`** |
| `__TEXT.__auth_stubs` | `0x430` | `0x420` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x228` | `0x220` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x148` | `0x140` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-980.67.2.0.0
+980.71.1.0.0

-  Symbols:   119
-  CStrings:  323
+  Symbols:   118
+  CStrings:  320
Symbols:
- _objc_opt_respondsToSelector
Functions:
~ sub_3e54 : 276 -> 220
~ sub_3f68 -> sub_3f30 : 200 -> 152
CStrings:
- "Error"
- "Unable to expedite email/SMS processing. This feature may not be supported on this device."
- "Unable to start Enhanced Owner Pairing. This feature may not be supported on this device."
```
