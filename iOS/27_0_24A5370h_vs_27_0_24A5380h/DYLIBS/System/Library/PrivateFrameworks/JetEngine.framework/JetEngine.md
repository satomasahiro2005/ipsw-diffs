## JetEngine

> `/System/Library/PrivateFrameworks/JetEngine.framework/JetEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4b32ec` | `0x4b76f4` | **`+0x4408`** |
| `__DATA_DIRTY.__data` | `0x510` | `0x210` | **`-0x300`** |
| `__TEXT.__eh_frame` | `0x25a54` | `0x25774` | **`-0x2e0`** |
| `__DATA.__data` | `0xd848` | `0xdb08` | **`+0x2c0`** |
| `__AUTH.__data` | `0x7a28` | `0x7c38` | **`+0x210`** |
| `__AUTH_CONST.__objc_const` | `0x9f58` | `0xa088` | **`+0x130`** |
| `__AUTH_CONST.__const` | `0x32500` | `0x32600` | **`+0x100`** |
| `__DATA.__bss` | `0x35bb0` | `0x35cb0` | **`+0x100`** |
| `__DATA_DIRTY.__bss` | `0x208` | `0x108` | **`-0x100`** |
| `__TEXT.__cstring` | `0x129c6` | `0x12a86` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0xc148` | `0xc1fc` | **`+0xb4`** |
| `__TEXT.__constg_swiftt` | `0xd7e4` | `0xd880` | **`+0x9c`** |
| `__TEXT.__const` | `0x9b688` | `0x9b718` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x7a0b` | `0x7a9b` | **`+0x90`** |
| `__AUTH.__objc_data` | `0x2598` | `0x25e8` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x2ae8` | `0x2b18` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0xf026` | `0xf056` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x11838` | `0x11808` | **`-0x30`** |
| `__TEXT.__swift_as_entry` | `0x9e4` | `0x9d0` | **`-0x14`** |
| `__TEXT.__swift_as_ret` | `0xa80` | `0xa6c` | **`-0x14`** |
| `__DATA_CONST.__got` | `0xe88` | `0xe98` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x874c` | `0x875c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x1044` | `0x1050` | **`+0xc`** |
| `__DATA.__common` | `0x840` | `0x848` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x498` | `0x4a0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1900` | `0x1908` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x13e0` | `0x13d8` | **`-0x8`** |

### Other Changes

```diff

-10.0.38.0.0
+10.0.42.0.0

-  Functions: 22547
-  Symbols:   7373
-  CStrings:  1904
+  Functions: 22573
+  Symbols:   7385
+  CStrings:  1908
Symbols:
+ __DATA__TtC9JetEngine13ObservableBag
+ __IVARS__TtC9JetEngine13ObservableBag
+ __METACLASS_DATA__TtC9JetEngine13ObservableBag
+ ___swift_closure_destructor.138Tm
+ ___swift_closure_destructor.146Tm
+ ___swift_closure_destructor.149Tm
+ ___swift_closure_destructor.152Tm
+ ___swift_closure_destructor.159Tm
+ ___swift_closure_destructor.285Tm
+ ___swift_closure_destructor.403Tm
+ ___swift_memcpy113_8
+ _symbolic SaySSSgG
+ _symbolic _____ 29AppleMediaServicesKitInternal10BagServiceV
+ _symbolic _____ 29AppleMediaServicesKitInternal10BagServiceV16ObservationTokenV
+ _symbolic _____ 9JetEngine13ObservableBagC
+ _symbolic _____ 9JetEngine13ObservableBagC17InvalidationTokenV
+ _symbolic _____ 9JetEngine7JSStackC19RecentlyReportedIDs33_4A282C0F868AC967FB12F8A19DFDC981LLV
+ _symbolic _____SgXw 9JetEngine19AssetSQLiteDatabaseC
+ _symbolic ______pSg So24OS_dispatch_source_timerP
+ _symbolic ______pSg So33OS_dispatch_source_memorypressureP
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 9JetEngine7JSStackC19RecentlyReportedIDs33_4A282C0F868AC967FB12F8A19DFDC981LLV
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 9JetEngine7JSStackC19RecentlyReportedIDs33_4A282C0F868AC967FB12F8A19DFDC981LLV So16os_unfair_lock_sV
+ _type_layout_string 9JetEngine7JSStackC19RecentlyReportedIDs33_4A282C0F868AC967FB12F8A19DFDC981LLV
- ___swift_closure_destructor.133Tm
- ___swift_closure_destructor.141Tm
- ___swift_closure_destructor.144Tm
- ___swift_closure_destructor.147Tm
- ___swift_closure_destructor.154Tm
- ___swift_closure_destructor.280Tm
- ___swift_closure_destructor.398Tm
- _get_type_metadata 15Synchronization5MutexVy9JetEngine16JSSourceProvider_pG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy9JetEngine12DiskPropertyOAD06CachedeF033_3D988632E755F3184F7A0396680788AELLVGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____AA______pIegnrzo_ 9JetEngine18LintedMetricsEventV s5ErrorP
CStrings:
+ "$exceptionReportID"
+ "PRAGMA wal_checkpoint(TRUNCATE)"
+ "Tearing down asset database ("
+ "Tearing down asset database (transaction ended)"
+ "WAL checkpoint before teardown failed: "
+ "com.apple.JetEngine.AssetSQLiteDatabase.teardown"
- "$exceptionHandled"
- "Tearing down asset database"
```
