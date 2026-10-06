## usermanagerd

> `/usr/libexec/usermanagerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xadff0` | `0xae2a0` | **`+0x2b0`** |
| `__DATA_CONST.__cfstring` | `0x1cc0` | `0x1d60` | **`+0xa0`** |
| `__TEXT.__const` | `0x1434` | `0x14a4` | **`+0x70`** |
| `__TEXT.__cstring` | `0x765b` | `0x76b9` | **`+0x5e`** |
| `__DATA_CONST.__got` | `0x1d0` | `0x208` | **`+0x38`** |
| `__DATA.__data` | `0x12c0` | `0x12f0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x27c0` | `0x27e8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x18c0` | `0x18d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xc70` | `0xc78` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1560` | `0x1568` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-  Functions: 2400
-  Symbols:   468
-  CStrings:  3386
+  Functions: 2406
+  Symbols:   469
+  CStrings:  3391
Symbols:
+ _CFArrayContainsValue
CStrings:
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "VolumeBagVEKCacheStatus"
```
