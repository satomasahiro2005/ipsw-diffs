## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/SpotlightIndex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4838d4` | `0x485704` | **`+0x1e30`** |
| `__TEXT.__oslogstring` | `0x1e202` | `0x1e59a` | **`+0x398`** |
| `__DATA_CONST.__const` | `0x8a70` | `0x8aa0` | **`+0x30`** |
| `__TEXT.__cstring` | `0x2f524` | `0x2f54f` | **`+0x2b`** |
| `__TEXT.__unwind_info` | `0x5b68` | `0x5b90` | **`+0x28`** |
| `__DATA.__bss` | `0x4010` | `0x4000` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1f38` | `0x1f40` | **`+0x8`** |

### Other Changes

```diff

-  Functions: 7758
-  Symbols:   10271
-  CStrings:  8090
+  Functions: 7768
+  Symbols:   10286
+  CStrings:  8110
Symbols:
+ GCC_except_table3831
+ GCC_except_table3836
+ GCC_except_table5079
+ GCC_except_table5082
+ GCC_except_table6768
+ __sdb_cache_check_fault
+ __tus_check_fault
+ __tus_protect
+ __tus_unprotect
+ __wrcache_arm_slot
+ __wrcache_free_page
+ _arc4random_uniform
+ _db_cache_call_with_entry
+ _db_cache_dealloc
+ _db_cache_protect_entry
+ _db_cache_unprotect_entry
+ _s_mprotect_registry
+ _s_mprotect_registry_capacity
+ _s_mprotect_registry_count
+ _s_mprotect_registry_lock
- GCC_except_table3821
- GCC_except_table3826
- GCC_except_table5069
- GCC_except_table5072
- GCC_except_table6758
CStrings:
+ "???"
+ "ARM"
+ "DISARM"
+ "FREE"
+ "NONE"
+ "PROTECT"
+ "SDB cache %p slot %d op[oldest+%d]: %{public}s dbp=%p"
+ "SDB cache %p slot %d: dbp=%p guarded=%d eligible=%d sz=%zu pgnum=0x%x"
+ "TUS kMDSTagUpdateSetPositionInfo guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetPositionTable guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetPostings guard fault: addr=%p base=%p size=%zu"
+ "TUS kMDSTagUpdateSetTerms (dataAllocator) guard fault: addr=%p slab=%p size=%zu"
+ "TUS kMDSTagUpdateSetTerms (termSlab) guard fault: addr=%p slab=%p size=%zu"
+ "UNPROTECT"
+ "Write cache %p: page lost mprotect eligibility after resize (new_ptr=%p, aligned=%d, dbp_sz=%d, page_sz=%zu)"
+ "Write cache %p: slot %d page %p armed for mprotect guard"
+ "Write cache %p: slot %d page %p freed (was guarded, sz=%zu)"
+ "Write cache %p: slot %d page changed from %p to %p after flush — clearing stale mprotect guard"
+ "mprotect failed: ptr=%p sz=%zu prot=%d errno=%d"
+ "mprotect guard fault at %p: could not acquire registry lock"
```
