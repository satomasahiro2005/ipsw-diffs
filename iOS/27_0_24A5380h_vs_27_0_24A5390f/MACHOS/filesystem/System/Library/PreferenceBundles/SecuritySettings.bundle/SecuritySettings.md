## SecuritySettings

> `/System/Library/PreferenceBundles/SecuritySettings.bundle/SecuritySettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__objc_const` | `0x1050` | `0x1080` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x24d8` | `0x2504` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0xa2c` | `0xa44` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xbb8` | `0xbc8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  CStrings:  626
+  CStrings:  628
CStrings:
+ "grammarCheckingType"
+ "setGrammarCheckingType:"
```
