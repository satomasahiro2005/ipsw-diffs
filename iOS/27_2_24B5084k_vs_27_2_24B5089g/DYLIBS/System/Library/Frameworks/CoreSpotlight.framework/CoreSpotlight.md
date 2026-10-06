## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x5b90` | `0x5618` | **`-0x578`** |
| `__DATA_DIRTY.__objc_data` | `0xe10` | `0x1388` | **`+0x578`** |
| `__TEXT.__text` | `0x17cee0` | `0x17d220` | **`+0x340`** |
| `__AUTH_CONST.__objc_const` | `0x1f7c0` | `0x1f820` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x2de60` | `0x2de80` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x14420` | `0x14440` | **`+0x20`** |
| `__TEXT.__cstring` | `0x2bc42` | `0x2bc60` | **`+0x1e`** |
| `__DATA_CONST.__objc_selrefs` | `0xa4c0` | `0xa4d8` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x5f48` | `0x5f60` | **`+0x18`** |
| `__DATA.__bss` | `0x19a0` | `0x1990` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xa7f8` | `0xa808` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x13f8` | `0x1400` | **`+0x8`** |

### Other Changes

```diff

-2465.1.2.0.0
+2465.1.3.0.0

-  Functions: 8866
-  Symbols:   14507
-  CStrings:  8075
+  Functions: 8869
+  Symbols:   14514
+  CStrings:  8077
Symbols:
+ -[CSSearchQueryContext allDisabledBundlesSet]
+ -[CSSearchQueryContext federationDisabledBundles]
+ -[CSSearchQueryContext setFederationDisabledBundles:]
+ GCC_except_table342
+ GCC_except_table356
+ GCC_except_table364
+ GCC_except_table369
+ GCC_except_table378
+ GCC_except_table385
+ GCC_except_table387
+ GCC_except_table391
+ GCC_except_table395
+ GCC_except_table403
+ GCC_except_table478
+ GCC_except_table479
+ GCC_except_table480
+ GCC_except_table487
+ GCC_except_table524
+ GCC_except_table571
+ _OBJC_IVAR_$_CSSearchQueryContext._allDisabledBundlesSet
+ _OBJC_IVAR_$_CSSearchQueryContext._federationDisabledBundles
- GCC_except_table339
- GCC_except_table353
- GCC_except_table375
- GCC_except_table376
- GCC_except_table384
- GCC_except_table388
- GCC_except_table389
- GCC_except_table394
- GCC_except_table474
- GCC_except_table475
- GCC_except_table476
- GCC_except_table484
- GCC_except_table521
- GCC_except_table568
CStrings:
+ "fdb"
+ "federationDisabledBundles"
```
