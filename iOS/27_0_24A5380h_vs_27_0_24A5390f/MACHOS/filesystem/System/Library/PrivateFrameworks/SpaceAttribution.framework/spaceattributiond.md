## spaceattributiond

> `/System/Library/PrivateFrameworks/SpaceAttribution.framework/spaceattributiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f8fc` | `0x3fac4` | **`+0x1c8`** |
| `__DATA_CONST.__const` | `0x1790` | `0x17e0` | **`+0x50`** |
| `__TEXT.__cstring` | `0x359d` | `0x35e4` | **`+0x47`** |
| `__DATA_CONST.__cfstring` | `0x2d80` | `0x2da0` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x500` | `0x510` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xe50` | `0xe58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-491.0.0.0.0
+493.0.0.502.1

-  Functions: 1468
-  Symbols:   244
-  CStrings:  2774
+  Functions: 1470
+  Symbols:   246
+  CStrings:  2775
Symbols:
+ _dispatch_block_perform
+ _objc_retain_x9
CStrings:
+ "bundleIDs %@ cache size: %llu is greater than existing data size: %llu"
```
