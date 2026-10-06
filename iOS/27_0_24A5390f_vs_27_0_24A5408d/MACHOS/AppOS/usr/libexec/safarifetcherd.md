## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x2460` | `0x2480` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x542e` | `0x5445` | **`+0x17`** |
| `__DATA.__objc_selrefs` | `0x1180` | `0x1188` | **`+0x8`** |
| `__TEXT.__text` | `0x96ac` | `0x96b4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.24.10.1
+7625.1.29.10.3

-  CStrings:  1020
+  CStrings:  1021
Functions:
~ sub_100008220 : 596 -> 604
CStrings:
+ "safari_isHTTPFamilyURL"
```
