## libhwtrace.dylib

> `/usr/lib/libhwtrace.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2760b4` | `0x27a5e8` | **`+0x4534`** |
| `__TEXT.__cstring` | `0x16943` | `0x16a53` | **`+0x110`** |
| `__DATA.__data` | `0x50` | `0x70` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x30070` | `0x30090` | **`+0x20`** |
| `__TEXT.__const` | `0x175f40` | `0x175f50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x31e8` | `0x31f8` | **`+0x10`** |

### Other Changes

```diff

-328.0.6.0.0
+328.0.9.0.0

-  Functions: 4842
+  Functions: 4859

-  CStrings:  4309
+  CStrings:  4319
CStrings:
+ "Compression-"
+ "DSC::__stub_region"
+ "__TEXT"
+ "__stub_region_"
+ "__text"
+ "dyld_shared_cache_for_each_unattributed_range"
+ "dyld_shared_cache_get_cpu_subtype"
+ "dyld_shared_cache_get_cpu_type"
+ "dyld_shared_cache_range_type_all_code"
+ "libhwtrace @ tag libhwtrace-328.0.9"
+ "libhwtrace @ tag libhwtrace-328.0.9\n"
+ "tag libhwtrace-328.0.9"
+ "v32@?0Q8Q16^{dispatch_data_s=}24"
- "libhwtrace @ tag libhwtrace-328.0.6"
- "libhwtrace @ tag libhwtrace-328.0.6\n"
- "tag libhwtrace-328.0.6"
```
