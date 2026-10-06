## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/SpotlightIndex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x483c40` | `0x482d88` | **`-0xeb8`** |
| `__TEXT.__cstring` | `0x2f2f2` | `0x2f434` | **`+0x142`** |
| `__TEXT.__oslogstring` | `0x1dda1` | `0x1ddf2` | **`+0x51`** |
| `__DATA.__bss` | `0x4040` | `0x3ff0` | **`-0x50`** |
| `__DATA_DIRTY.__bss` | `0x9c78` | `0x9cc8` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x5b50` | `0x5b68` | **`+0x18`** |

### Other Changes

```diff

-2465.1.2.0.0
+2465.1.3.0.0

-  Functions: 7750
-  Symbols:   10261
-  CStrings:  8055
+  Functions: 7755
+  Symbols:   10266
+  CStrings:  8072
Symbols:
+ GCC_except_table220
+ GCC_except_table227
+ GCC_except_table3821
+ GCC_except_table3826
+ GCC_except_table5069
+ GCC_except_table5072
+ GCC_except_table6755
+ __ZN19PartialQueryResults21cannedAttributeVectorEv
+ __ZN19PartialQueryResults28cannedCollectAttributeVectorEv
+ __ZN19PartialQueryResults29cannedRequiredAttributeVectorEv
+ __si_finish_property_write
+ __si_set_property_locked
+ __si_write_property_data
- GCC_except_table222
- GCC_except_table229
- GCC_except_table3823
- GCC_except_table3828
- GCC_except_table5075
- GCC_except_table5078
- GCC_except_table6758
- __ZN19PartialQueryResults34setupCannedRequiredAttributeVectorEPPKcPPPFS2_P4__SIE
CStrings:
+ "%s:%d: <si:%s> - Failed to mark the store dirty after a property write, rc:%d"
+ "2465.1.3"
+ "<si:%s> - Suspending preheat scheduler for %p (%s)"
+ "_attributeVector"
+ "_completionAttributeVector"
+ "_si_finish_property_write"
+ "_si_write_property_data"
+ "computeFlags"
+ "container_table_check"
+ "count < (CFIndex)UINT32_MAX && count >= 0"
+ "evaluateFuzzyQueryForIndex_block_invoke"
+ "kr == KERN_SUCCESS"
+ "oidArray"
+ "oidVector"
+ "ownOidArray"
+ "prepare"
+ "processPrefix"
+ "setOneFieldLocked"
+ "setupFieldIdVector"
+ "si_querypipe_addresults"
+ "suspendOthers"
+ "v40@?0^{__SI=Q{SIFileOps=^?^?^?}{SIGuardedFd=iQ}isII^{SIWatchDog}^{__CFDictionary}{_opaque_pthread_rwlock_t=q[192c]}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{os_unfair_lock_s=I}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}^{__CFDictionary}^{_MDPlistContainer}Bi[18^{si_scheduler_token_s}]iI[4^{dispatch_semaphore_s}]{?=[18^{_si_work_scheduler}][20^{_si_workqueue}]^{si_workqueue_list_s}}^{dispatch_queue_s}^{datastore_info}{CIMetaInfo=i^{fd_obj}iQIIIIIIIIqqiiBI}^{DocStore}QQ{_opaque_pthread_mutex_t=q[56c]}^{ContentIndexList}^{ContentIndexList}iII^{_SI_PersistentIDStore}{__SIStoreToken={?=CCCCCCCCCCCCCCCC}^{__CFUUID}}ACAII{os_unfair_lock_s=I}ddBiI^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{os_unfair_lock_s=I}^{__CFBag}{_opaque_pthread_mutex_t=q[56c]}^{__CFSet}^{__CFDictionary}Q^{__CFBag}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_cond_t=q[40c]}iIIIIIIIIIIIIIIIIIIIIBBBAq^{__CFDictionary}^{__CFBitVector}^{__CFDictionary}^{__CFArray}^{si_mobile_journal}^{si_mobile_journal}^{si_mobile_journal}AqAqAq^{dispatch_source_s}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}^{__CFArray}Cd^?^vdd{?=^{fd_obj}IIIq{os_unfair_lock_s=I}BB^vQQQQAB}III^{FinderDateFields}{_opaque_pthread_mutex_t=q[56c]}^{fd_obj}^{fd_obj}^{fd_obj}iii^{_SIIndexCallbacks}^{__CFArray}^{__CFArray}qqqQIIiiBBBBBBBABB^{si_scheduler_token_s}BBBBBBQq[4096c]{os_unfair_lock_s=I}{os_unfair_lock_s=I}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b2b1b1^i^{__CFSet}^{__CFDictionary}^{__SIUINT64Set}^{ReverseDirStore_s}^{FileTree_Overlay_s}^{__CFSet}^{TermUpdateSet}{_opaque_pthread_rwlock_t=q[192c]}[16C]Bi^{datastore_info}AIBB[5i]*iI^vB^{fd_obj}iiii{AccumulatedCounts_s={_opaque_pthread_mutex_t=q[56c]}[256q][256I][256I]}BB^{si_analytics_s}}8^{_xpc_activity_s=}16^B24^{dispatch_group_s=}32"
- "2465.1.2"
- "<si:%s> - Suspending root scheduler for %p (%s)"
- "_si_store_property_cache"
- "count < (CFIndex)4294967295U && count >= 0"
- "v40@?0^{__SI=Q{SIFileOps=^?^?^?}{SIGuardedFd=iQ}isII^{SIWatchDog}^{__CFDictionary}{_opaque_pthread_rwlock_t=q[192c]}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{si_missing_oids_s={os_unfair_lock_s=I}^{__RLEOIDArray}^{__RLEOIDArray}}{os_unfair_lock_s=I}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}{si_comm_dates_s=^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}^{__CFBag}}^{__CFDictionary}^{_MDPlistContainer}Bi[18^{si_scheduler_token_s}]iI[4^{dispatch_semaphore_s}]{?=[18^{_si_work_scheduler}][20^{_si_workqueue}]^{si_workqueue_list_s}}^{dispatch_queue_s}^{datastore_info}{CIMetaInfo=i^{fd_obj}iQIIIIIIIIqqiiBI}^{DocStore}QQ{_opaque_pthread_mutex_t=q[56c]}^{ContentIndexList}^{ContentIndexList}iII^{_SI_PersistentIDStore}{__SIStoreToken={?=CCCCCCCCCCCCCCCC}^{__CFUUID}}ACAII{os_unfair_lock_s=I}ddBiI^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{os_unfair_lock_s=I}^{__CFBag}{_opaque_pthread_mutex_t=q[56c]}^{__CFSet}^{__CFDictionary}Q^{__CFBag}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_mutex_t=q[56c]}{_opaque_pthread_cond_t=q[40c]}iIIIIIIIIIIIIIIIIIIIIBBBAq^{__CFDictionary}^{__CFBitVector}^{__CFDictionary}^{__CFArray}^{si_mobile_journal}^{si_mobile_journal}^{si_mobile_journal}AqAqAq^{dispatch_source_s}^{__CFDictionary}{_opaque_pthread_mutex_t=q[56c]}^{__CFArray}Cd^?^vdd{?=^{fd_obj}IIIq{os_unfair_lock_s=I}BB^vQQQQAB}III^{FinderDateFields}{_opaque_pthread_mutex_t=q[56c]}^{fd_obj}^{fd_obj}^{fd_obj}iii^{_SIIndexCallbacks}^{__CFArray}^{__CFArray}qqqQIIiiBBBBBBBABB^{si_scheduler_token_s}BBBBBBQq[4096c]{os_unfair_lock_s=I}{os_unfair_lock_s=I}b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b1b2b1b1^i^{__CFSet}^{__CFDictionary}^{__SIUINT64Set}^{ReverseDirStore_s}^{FileTree_Overlay_s}^{__CFSet}^{TermUpdateSet}{_opaque_pthread_rwlock_t=q[192c]}[16C]Bi^{datastore_info}AIBB[5i]*iI^vB^{fd_obj}iiii{AccumulatedCounts_s={_opaque_pthread_mutex_t=q[56c]}[256q][256I][256I]}BB^{si_analytics_s}}8^{_xpc_activity_s=}16^B24^{dispatch_group_s=}32"
```
