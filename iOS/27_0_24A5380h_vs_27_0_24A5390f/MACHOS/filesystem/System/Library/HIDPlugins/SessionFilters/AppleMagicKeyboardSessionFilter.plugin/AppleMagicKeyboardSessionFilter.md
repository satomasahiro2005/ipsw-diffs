## AppleMagicKeyboardSessionFilter

> `/System/Library/HIDPlugins/SessionFilters/AppleMagicKeyboardSessionFilter.plugin/AppleMagicKeyboardSessionFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4954` | `0x4978` | **`+0x24`** |
| `__DATA_CONST.__cfstring` | `0x6c0` | `0x6e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x331` | `0x343` | **`+0x12`** |
| `__TEXT.__auth_stubs` | `0x410` | `0x420` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x218` | `0x220` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-9170.17.0.0.0
+10100.22.0.0.0

+  - /usr/lib/libMobileGestalt.dylib

-  Symbols:   102
-  CStrings:  382
+  Symbols:   103
+  CStrings:  383
Symbols:
+ _MGGetSInt32Answer
Functions:
~ sub_2ef4 -> sub_2f34 : 384 -> 420
CStrings:
+ "DeviceClassNumber"
```
