## diskimagespawner

> `/usr/libexec/diskimagespawner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x250b0` | `0x24ff8` | **`-0xb8`** |
| `__TEXT.__objc_methname` | `0xaff` | `0xaa6` | **`-0x59`** |
| `__TEXT.__objc_methlist` | `0x43c` | `0x424` | **`-0x18`** |
| `__TEXT.__objc_methtype` | `0x4a8` | `0x491` | **`-0x17`** |
| `__DATA.__objc_selrefs` | `0x368` | `0x358` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-593.0.0.0.1
+596.0.0.0.0

-  Functions: 945
+  Functions: 943

-  CStrings:  353
+  CStrings:  350
CStrings:
+ "errorWithDIException:prefix:error:"
- "@48@0:8r^v16@24@32^@40"
- "errorWithDIException:description:prefix:error:"
- "failWithDIException:description:error:"
- "nilWithDIException:description:error:"
```
