## coreauthd

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/coreauthd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x381d4` | `0x38468` | **`+0x294`** |
| `__DATA_CONST.__cfstring` | `0xcc0` | `0xd60` | **`+0xa0`** |
| `__TEXT.__const` | `0x13f8` | `0x1468` | **`+0x70`** |
| `__TEXT.__cstring` | `0x5010` | `0x506e` | **`+0x5e`** |
| `__DATA.__data` | `0x1b38` | `0x1b68` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x20a0` | `0x20c8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xe30` | `0xe50` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5e0` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x728` | `0x738` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd28` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2319.0.16.502.1
+2319.0.33.0.1

-  Functions: 1555
-  Symbols:   425
-  CStrings:  1833
+  Functions: 1561
+  Symbols:   427
+  CStrings:  1838
Symbols:
+ _CFArrayContainsValue
+ _CFArrayGetCount
CStrings:
+ "GroupSeedGeneration"
+ "GroupSeedKCV"
+ "GroupSeedWrappingType"
+ "GroupUserCount"
+ "VolumeBagVEKCacheStatus"
```
