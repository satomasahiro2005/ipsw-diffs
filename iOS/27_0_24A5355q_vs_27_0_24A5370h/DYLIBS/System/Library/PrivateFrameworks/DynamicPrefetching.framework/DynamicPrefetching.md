## DynamicPrefetching

> `/System/Library/PrivateFrameworks/DynamicPrefetching.framework/DynamicPrefetching`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17b08` | `0x17fe4` | **`+0x4dc`** |
| `__TEXT.__oslogstring` | `0x22ba` | `0x24ea` | **`+0x230`** |
| `__TEXT.__gcc_except_tab` | `0x1180` | `0x11f4` | **`+0x74`** |
| `__DATA.__bss` | `0x1c0` | `0x228` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x7e0` | `0x830` | **`+0x50`** |
| `__TEXT.__cstring` | `0x832` | `0x86c` | **`+0x3a`** |
| `__DATA_CONST.__const` | `0x208` | `0x230` | **`+0x28`** |
| `__DATA.__data` | `0x108` | `0xe8` | **`-0x20`** |
| `__TEXT.__const` | `0x49e` | `0x4ae` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Other Changes

```diff

-3.5.2.0.0
+3.5.5.0.0

-  Functions: 459
+  Functions: 483

-  CStrings:  248
+  CStrings:  256
Symbols:
+ _dispatch_after
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEaSERKS5_
CStrings:
+ "  profile_size_cap_mb:      %llu\n  fresh_age_threshold:      %llu\n  stale_age_threshold:      %llu\n  order:                    %s\n  num_prefetching_threads:  %u\n  prefetching_io_stride:    %u\n  prefetch_start_delay_ms:  %u"
+ "Settings: prefetch_start_delay_ms=%u exceeds cap %u, clamping"
+ "fd_guard::reset close failed on fd %d with error %{darwin.errno}d"
+ "mmapped_profile: prefetch_results is full."
+ "prefetch_start_delay_ms"
+ "start_scenario: deferred prefetch exception for bundleid %{public}@ : %{public}s"
+ "start_scenario: deferred prefetch skipped for bundleid \"%s\" scenario \"%s\" — scenario no longer active"
+ "start_scenario: deferred prefetch unknown exception for bundleid %{public}@"
+ "start_scenario: deferred prefetch-only exception for bundleid %{public}@ : %{public}s"
+ "start_scenario: deferred prefetch-only unknown exception for bundleid %{public}@"
+ "start_scenario: duplicate call for active bundleid \"%s\" scenario \"%s\""
- "  profile_size_cap_mb:      %llu\n  fresh_age_threshold:      %llu\n  stale_age_threshold:      %llu\n  order:                    %s\n  num_prefetching_threads:  %u\n  prefetching_io_stride: %u"
- "mmapped_profile: deferred_file_updates is full."
- "start_scenario: called twice for bundleid \"%s\" scenario \"%s\""
```
