## com.apple.siri.embeddedspeech

> `/System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/XPCServices/com.apple.siri.embeddedspeech.xpc/com.apple.siri.embeddedspeech`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0x818` | `0x858` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x83a0` | `0x83c0` | **`+0x20`** |
| `__TEXT.__text` | `0x331ac` | `0x331cc` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x24d0` | `0x24d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x780` | `0x788` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0xa515` | `0xa51c` | **`+0x7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-3600.70.8.0.0
+3600.70.20.1.1

-  CStrings:  2546
+  CStrings:  2547
Functions:
~ sub_10000cf54 : 296 -> 328
CStrings:
+ "dataUsingEncoding:"
+ "writeToURL:options:error:"
- "writeToURL:atomically:encoding:error:"
```
