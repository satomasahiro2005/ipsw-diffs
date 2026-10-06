## transparencyStaticKey

> `/usr/libexec/transparencyStaticKey`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b214` | `0x6b294` | **`+0x80`** |
| `__DATA.__objc_const` | `0xb560` | `0xb590` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x820b` | `0x822c` | **`+0x21`** |
| `__DATA_CONST.__cfstring` | `0x2fe0` | `0x3000` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x6760` | `0x6780` | **`+0x20`** |
| `__TEXT.__cstring` | `0x23b8` | `0x23d4` | **`+0x1c`** |
| `__TEXT.__objc_methlist` | `0x7c18` | `0x7c30` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x2438` | `0x2448` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x27e8` | `0x27f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1766.0.27.0.0
+1766.0.39.0.2

-  Functions: 3719
+  Functions: 3720

-  CStrings:  2785
+  CStrings:  2788
Functions:
~ sub_100034408 : 12 -> 128
+ sub_100034488
CStrings:
+ "apns-ids-query-percentage-2"
+ "integerValue"
+ "webTunnelPercentage"
```
