## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x2fd4` | `0x3003` | **`+0x2f`** |
| `__TEXT.__objc_stubs` | `0x3380` | `0x33a0` | **`+0x20`** |
| `__TEXT.__text` | `0x59ce0` | `0x59cec` | **`+0xc`** |
| `__DATA.__objc_selrefs` | `0xe60` | `0xe68` | **`+0x8`** |

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
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.40.49.502.1
+62460.40.56.502.1

-  CStrings:  2215
+  CStrings:  2216
Functions:
~ sub_10002e354 : 380 -> 392
CStrings:
+ "_setPrivacyProxyFailClosedForUnreachableHosts:"
```
