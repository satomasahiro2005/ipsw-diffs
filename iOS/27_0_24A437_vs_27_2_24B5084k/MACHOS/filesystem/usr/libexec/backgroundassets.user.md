## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5abe4` | `0x5ad3c` | **`+0x158`** |
| `__TEXT.__objc_methname` | `0x9cae` | `0x9cde` | **`+0x30`** |
| `__DATA.__objc_selrefs` | `0x21b8` | `0x21c0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x352c` | `0x3534` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-279.0.5.0.0
+279.40.6.0.0

-  Functions: 1948
+  Functions: 1949

-  CStrings:  2619
+  CStrings:  2620
Functions:
~ sub_10001572c : 424 -> 344
+ sub_100015884
CStrings:
+ "_pauseBackgroundDownloads"
+ "pauseAllBackgroundDownloads"
- "_pauseDownloads"
```
