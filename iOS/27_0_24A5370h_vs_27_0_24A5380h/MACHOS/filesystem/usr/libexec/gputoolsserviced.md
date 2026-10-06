## gputoolsserviced

> `/usr/libexec/gputoolsserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33024` | `0x33060` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x268` | `0x288` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x55c0` | `0x55e0` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x7756` | `0x7770` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0x1db8` | `0x1dc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2027.0.31.0.0
+2027.0.33.0.0

-  CStrings:  2089
+  CStrings:  2090
Functions:
~ sub_1000091a8 : 10580 -> 10620
~ sub_10000c3b4 -> sub_10000c3dc : 372 -> 392
CStrings:
+ "supportsMultiPlaneTensors"
```
