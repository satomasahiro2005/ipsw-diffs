## CoreSpotlight

> `/System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x180300` | `0x1805c8` | **`+0x2c8`** |
| `__TEXT.__oslogstring` | `0xbf0c` | `0xbfee` | **`+0xe2`** |
| `__AUTH_CONST.__objc_const` | `0x20100` | `0x20120` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x6060` | `0x6070` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xe70` | `0xe78` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xa618` | `0xa620` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1468` | `0x146c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-2465.1.7.0.0
+2465.1.9.0.0

-  Functions: 8955
-  Symbols:   14690
-  CStrings:  8104
+  Functions: 8959
+  Symbols:   14692
+  CStrings:  8107
Symbols:
+ _NSURLFileSizeKey
+ _OBJC_IVAR_$_CSFileProviderDomainMonitor._savedRemovedCount
CStrings:
+ "At the %lu removed FP domain ceiling; not tracking further removals"
+ "Discarding saved FP domain list: %llu bytes exceeds the %llu byte budget"
+ "Saved FP domain list holds %lu entries; tracking the first %lu and ignoring the rest"
```
