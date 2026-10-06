## JetCore

> `/System/Library/PrivateFrameworks/JetCore.framework/JetCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x260f00` | `0x264498` | **`+0x3598`** |
| `__DATA.__bss` | `0x23410` | `0x23190` | **`-0x280`** |
| `__DATA_DIRTY.__bss` | `0x5690` | `0x5910` | **`+0x280`** |
| `__TEXT.__eh_frame` | `0x15110` | `0x14f78` | **`-0x198`** |
| `__AUTH.__data` | `0x2540` | `0x2670` | **`+0x130`** |
| `__DATA_DIRTY.__data` | `0x35d8` | `0x3708` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x2a40` | `0x2b68` | **`+0x128`** |
| `__TEXT.__cstring` | `0xa401` | `0xa4c1` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x7ab4` | `0x7b2c` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x69a0` | `0x6a14` | **`+0x74`** |
| `__AUTH_CONST.__auth_got` | `0x1ed0` | `0x1f40` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x1a288` | `0x1a2f8` | **`+0x70`** |
| `__TEXT.__const` | `0x1e9fc` | `0x1ea6c` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x3ac2` | `0x3b32` | **`+0x70`** |
| `__AUTH.__objc_data` | `0x528` | `0x578` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x8319` | `0x8349` | **`+0x30`** |
| `__DATA.__data` | `0x6398` | `0x63c0` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x9988` | `0x9968` | **`-0x20`** |
| `__DATA.__common` | `0x400` | `0x3e8` | **`-0x18`** |
| `__DATA_DIRTY.__common` | `0xe8` | `0x100` | **`+0x18`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x78` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x36f8` | `0x3708` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x5ac` | `0x5a0` | **`-0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x140` | `0x148` | **`+0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x38` | `0x40` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x838` | `0x840` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x990` | `0x998` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xa5c` | `0xa58` | **`-0x4`** |

### Other Changes

```diff

-10.0.38.0.0
+10.0.42.0.0

-  Functions: 12689
-  Symbols:   3772
-  CStrings:  967
+  Functions: 12711
+  Symbols:   3783
+  CStrings:  971
Symbols:
+ __DATA__TtC7JetCore13ObservableBag
+ __IVARS__TtC7JetCore13ObservableBag
+ __METACLASS_DATA__TtC7JetCore13ObservableBag
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_timer
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_timer
+ __OBJC_PROTOCOL_$_OS_dispatch_source_timer
+ ___swift_closure_destructor.113Tm
+ ___swift_closure_destructor.136Tm
+ ___swift_closure_destructor.328Tm
+ ___swift_closure_destructor.7Tm
+ _flat unique So24OS_dispatch_source_timer_p
+ _symbolic Say_____G So18OS_dispatch_sourceC8DispatchE10TimerFlagsV
+ _symbolic _____ 29AppleMediaServicesKitInternal10BagServiceV
+ _symbolic _____ 29AppleMediaServicesKitInternal10BagServiceV16ObservationTokenV
+ _symbolic _____ 7JetCore13ObservableBagC
+ _symbolic _____ 7JetCore13ObservableBagC17InvalidationTokenV
+ _symbolic _____SgXw 7JetCore19AssetSQLiteDatabaseC
+ _symbolic ______pSg So24OS_dispatch_source_timerP
+ _symbolic ______pSg So33OS_dispatch_source_memorypressureP
- ___swift_closure_destructor.122Tm
- ___swift_closure_destructor.145Tm
- ___swift_closure_destructor.356Tm
- ___swift_closure_destructor.4Tm
- _get_type_metadata 15Synchronization5MutexVySDy7JetCore12DiskPropertyOAD06CachedeF033_AFE4BF2935A20D1EF71D00885BED2A8FLLVGG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _symbolic _____AA______pIegnrzo_ 7JetCore18LintedMetricsEventV s5ErrorP
- _symbolic ______pSg 7JetCore11IntentCacheP
CStrings:
+ "PRAGMA wal_checkpoint(TRUNCATE)"
+ "Tearing down asset database ("
+ "Tearing down asset database (transaction ended)"
+ "WAL checkpoint before teardown failed: "
+ "com.apple.JetEngine.AssetSQLiteDatabase.teardown"
- "Tearing down asset database"
```
