## HomeSettings

> `/System/Library/PreferenceBundles/HomeSettings.bundle/HomeSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b3c` | `0x5b7c` | **`+0x40`** |
| `__TEXT.__cstring` | `0x1312` | `0x1338` | **`+0x26`** |
| `__DATA_CONST.__cfstring` | `0x1560` | `0x1580` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x488` | `0x490` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1269.2.5.1.4
+1269.2.5.1.5

-  Symbols:   231
-  CStrings:  696
+  Symbols:   232
+  CStrings:  697
Symbols:
+ _HFPreferencesIgnoreSpeakerGroupingErrorsKey
Functions:
~ sub_4be0 : 6312 -> 6376
CStrings:
+ "Ignore Some Errors for Speaker Groups"
```
