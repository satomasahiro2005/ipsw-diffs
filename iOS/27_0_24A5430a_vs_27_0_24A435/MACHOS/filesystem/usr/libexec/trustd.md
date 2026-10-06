## trustd

> `/usr/libexec/trustd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59b58` | `0x59ce0` | **`+0x188`** |
| `__DATA_CONST.__cfstring` | `0x5d40` | `0x5da0` | **`+0x60`** |
| `__TEXT.__cstring` | `0x60c3` | `0x6115` | **`+0x52`** |
| `__TEXT.__objc_stubs` | `0x3360` | `0x3380` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x3dc8` | `0x3de0` | **`+0x18`** |
| `__TEXT.__objc_methname` | `0x2fbe` | `0x2fd4` | **`+0x16`** |
| `__DATA.__data` | `0x3f8` | `0x400` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0xe58` | `0xe60` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1018` | `0x1020` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-62460.2.2.0.0
+62460.2.3.0.0

-  Functions: 1202
+  Functions: 1204

-  CStrings:  2210
+  CStrings:  2214
CStrings:
+ "PhotoRevocationCheck"
+ "com.apple.private.trustd.prl-access"
+ "isPhotoRevoked:error:"
+ "photoID must be 32 bytes"
```
