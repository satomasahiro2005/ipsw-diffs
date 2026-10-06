## tvremoted

> `/usr/libexec/tvremoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x110d4` | `0x112d4` | **`+0x200`** |
| `__TEXT.__oslogstring` | `0x26d7` | `0x2716` | **`+0x3f`** |
| `__TEXT.__objc_methname` | `0x32b7` | `0x32e0` | **`+0x29`** |
| `__TEXT.__objc_stubs` | `0x2620` | `0x2640` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xf44` | `0xf54` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xcc8` | `0xcd0` | **`+0x8`** |

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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-627.0.28.0.0
+627.10.45.0.0

-  Functions: 333
+  Functions: 334

-  CStrings:  938
+  CStrings:  940
Functions:
~ sub_100008e3c : 464 -> 524
+ sub_10000fa20
CStrings:
+ "Not relinquishing %@ - a client connection is still interested"
+ "_hasInterestedClientConnectionForDevice:"
```
