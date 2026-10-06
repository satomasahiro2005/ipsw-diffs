## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x190060` | `0x18f77c` | **`-0x8e4`** |
| `__AUTH_CONST.__cfstring` | `0x12d40` | `0x12ce0` | **`-0x60`** |
| `__TEXT.__cstring` | `0x15c1e` | `0x15c4a` | **`+0x2c`** |
| `__DATA_CONST.__objc_arraydata` | `0x6e8` | `0x710` | **`+0x28`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x618` | `0x630` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5458` | `0x5450` | **`-0x8`** |

### Other Changes

```diff

-1956.0.1.0.0
+1959.0.1.0.0

-  Functions: 8783
+  Functions: 8782

-  CStrings:  4650
+  CStrings:  4647
CStrings:
+ "caseInsensitiveCompare:"
+ "compare:"
+ "localizedCaseInsensitiveCompare:"
+ "localizedCompare:"
+ "localizedStandardCompare:"
- "alloc"
- "autorelease"
- "dealloc"
- "finalize"
- "mutableCopy"
- "new"
- "release"
- "retain"
```
