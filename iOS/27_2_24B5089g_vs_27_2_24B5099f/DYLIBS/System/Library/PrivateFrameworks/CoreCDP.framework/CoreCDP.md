## CoreCDP

> `/System/Library/PrivateFrameworks/CoreCDP.framework/CoreCDP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f994` | `0x4fa10` | **`+0x7c`** |
| `__AUTH_CONST.__cfstring` | `0x3f40` | `0x3f80` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x610` | `0x630` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2fe8` | `0x2ff8` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x21d8` | `0x21e8` | **`+0x10`** |
| `__TEXT.__cstring` | `0x66aa` | `0x66ba` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x4f0` | `0x4f8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3aac` | `0x3ab4` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1668` | `0x1670` | **`+0x8`** |

### Other Changes

```diff

-448.125.5.2.0
+448.125.9.0.0

-  Functions: 2404
-  Symbols:   3903
-  CStrings:  1647
+  Functions: 2406
+  Symbols:   3908
+  CStrings:  1649
Symbols:
+ -[NSError(CDP) cdp_isTransientNetworkErrorIncludingUnderlyingErrors]
+ _NSURLErrorDomain
+ ___68-[NSError(CDP) cdp_isTransientNetworkErrorIncludingUnderlyingErrors]_block_invoke
+ _kDataAccessRecoveryContactSuggestionFamily
+ _kDataAccessRecoveryContactSuggestionMegadome
CStrings:
+ "family"
+ "megadome"
```
