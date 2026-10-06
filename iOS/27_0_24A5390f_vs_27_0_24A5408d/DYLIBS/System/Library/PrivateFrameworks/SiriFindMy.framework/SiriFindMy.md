## SiriFindMy

> `/System/Library/PrivateFrameworks/SiriFindMy.framework/SiriFindMy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1818e8` | `0x184a38` | **`+0x3150`** |
| `__TEXT.__oslogstring` | `0x70d5` | `0x74c5` | **`+0x3f0`** |
| `__AUTH_CONST.__const` | `0xe520` | `0xe5c0` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x1ce4` | `0x1d24` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x26d8` | `0x26f8` | **`+0x20`** |
| `__TEXT.__cstring` | `0x27e3` | `0x27c3` | **`-0x20`** |
| `__TEXT.__eh_frame` | `0xb25c` | `0xb23c` | **`-0x20`** |
| `__DATA.__common` | `0x4f8` | `0x510` | **`+0x18`** |
| `__DATA.__data` | `0x5108` | `0x5118` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x13f8` | `0x1408` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x5b74` | `0x5b84` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0xcd8` | `0xcd0` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x7ad6` | `0x7ad8` | **`+0x2`** |

### Other Changes

```diff

-3600.18.6.0.0
+3600.18.7.0.0

-  Functions: 10597
-  Symbols:   3038
-  CStrings:  788
+  Functions: 10624
+  Symbols:   3040
+  CStrings:  795
Symbols:
+ ___swift_closure_destructor.29Tm
+ ___swift_closure_destructor.74Tm
+ _symbolic _____Sg 7FMFCore11PlacedLabelV
- ___swift_closure_destructor.68Tm
CStrings:
+ "Cache file %{public}s does not exist"
+ "Could not parse %{public}s using PropertyListDecoder"
+ "Could not read data from cache file at %{public}s"
+ "Deleted old cache file at %{public}s"
+ "DiskCacher.evict: Could not delete the cache file at %{public}s due to %{public}s"
+ "DiskCacher.evict: No cache location available for this process; nothing to do"
+ "DiskCacher.getEntry: No cache location available for this process; reporting a cache miss"
+ "DiskCacher.getOldSystemCacheURL: Could not find cache directory"
+ "DiskCacher.getSystemCacheURL: Failed to get container URL for app group '%{public}s'. Disk caching is disabled for this process. This can happen if the running binary is not a member of the app group (missing/unsigned entitlement), the process is not running in a per-user sandboxed context, or the group container has not been provisioned."
+ "DiskCacher.removeOldCacheFile: Old cache file to delete: %{public}s"
+ "DiskCacher.setEntry: Could not write cache file %{public}s due to %{public}s"
+ "DiskCacher.setEntry: No cache location available for this process; skipping disk write"
+ "DiskCacher.setEntry: Wrote cache to %{public}s"
+ "Failed to delete old cache file at %{public}s due to %{public}s"
+ "group.com.apple.siri.findmy"
- "Cache file %s does not exist"
- "Could not delete the cache file at %s due to %{public}s"
- "Could not find cache directory"
- "Could not parse %s using PropertyListDecoder"
- "Could not read data from cache file at %s"
- "Could not write cache file %s due to %{public}s"
- "SiriFindMy/Caching.swift"
- "Wrote cache to %s"
```
