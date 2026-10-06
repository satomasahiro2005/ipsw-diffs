## powerexperienced

> `/usr/libexec/powerexperienced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1bdc8` | `0x1bf34` | **`+0x16c`** |
| `__TEXT.__oslogstring` | `0x3364` | `0x33a9` | **`+0x45`** |
| `__DATA_CONST.__cfstring` | `0x1460` | `0x14a0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x3c00` | `0x3c40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x137f` | `0x13bb` | **`+0x3c`** |
| `__DATA.__objc_const` | `0x59e0` | `0x5a10` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x259c` | `0x25cc` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x443b` | `0x444c` | **`+0x11`** |
| `__DATA.__objc_selrefs` | `0x1238` | `0x1240` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x288` | `0x28c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-182.0.0.0.0
+182.40.2.0.0

-  Functions: 878
+  Functions: 882

-  CStrings:  1485
+  CStrings:  1489
CStrings:
+ "AssertionTimeout"
+ "Overriding InBoxUpdateMode Assertion with defaults timeout value %ld"
+ "assertionTimeout"
+ "com.apple.powerexperienced.inboxupdatemode"
```
