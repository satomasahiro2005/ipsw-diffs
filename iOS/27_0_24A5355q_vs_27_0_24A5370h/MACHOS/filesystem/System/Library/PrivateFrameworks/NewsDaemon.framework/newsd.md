## newsd

> `/System/Library/PrivateFrameworks/NewsDaemon.framework/newsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x53eb0` | `0x54410` | **`+0x560`** |
| `__TEXT.__objc_methname` | `0x5ddd` | `0x5ebd` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x288d` | `0x27cd` | **`-0xc0`** |
| `__TEXT.__objc_stubs` | `0x4220` | `0x42c0` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x27c0` | `0x2760` | **`-0x60`** |
| `__DATA_CONST.__const` | `0x2618` | `0x25c0` | **`-0x58`** |
| `__TEXT.__swift5_reflstr` | `0x86c` | `0x81c` | **`-0x50`** |
| `__DATA.__objc_const` | `0x3c38` | `0x3c78` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x22a0` | `0x22e0` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0xd93` | `0xd65` | **`-0x2e`** |
| `__DATA.__objc_selrefs` | `0x1590` | `0x15b8` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0x898` | `0x870` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0x1160` | `0x1180` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x7f8` | `0x7d8` | **`-0x20`** |
| `__TEXT.__gcc_except_tab` | `0x1f8` | `0x218` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x1b23` | `0x1b43` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x19e0` | `0x19f8` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x14` | **`-0x14`** |
| `__DATA.__data` | `0x1ed0` | `0x1ec0` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x7a8` | `0x7b8` | **`+0x10`** |
| `__TEXT.__const` | `0x1e90` | `0x1e80` | **`-0x10`** |
| `__DATA.__objc_data` | `0xd80` | `0xd78` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x108` | `0x110` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x5b0` | `0x5a8` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x1428` | `0x1420` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0xa8` | `0xa4` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x1b4` | `0x1b8` | **`+0x4`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 1479
-  Symbols:   975
-  CStrings:  1516
+  Functions: 1475
+  Symbols:   980
+  CStrings:  1524
Symbols:
+ _$s10NewsDaemon21NDSystemScheduledWorkC10identifier8priority4workACSS_AA0cdE8PriorityOyyYaYbctcfC
+ _$s10NewsDaemon21NDSystemScheduledWorkC11setNeedsRunyyF
+ _$s10NewsDaemon21NDSystemScheduledWorkCMa
+ _$s10NewsDaemon21NDSystemScheduledWorkCMn
+ _$sS2cEycfC
+ _$sScEMa
+ _$sScEs5ErrorsMc
+ _$sScTss5NeverORszABRs_rlE17checkCancellationyyKFZ
+ _$ss5Int64VMn
+ _OBJC_CLASS_$_NDSystemScheduledWork
+ _objc_getProperty
+ _objc_setProperty_atomic_copy
- _$s2os21OSAllocatedUnfairLockVMn
- _$sScP13userInitiatedScPvgZ
- _$ss13ManagedBufferCMn
- _$ss6UInt32VMn
- _os_unfair_lock_lock
- _os_unfair_lock_unlock
- _swift_release_x9
CStrings:
+ "\t"
+ "@\"NDSystemScheduledWork\""
+ "@\"NSData\""
+ "T@\"NDSystemScheduledWork\",R,N,V_configAdoptionWork"
+ "T@\"NSData\",C,V_pendingConfigData"
+ "TodayFeedService will schedule feed config adoption, length=%lu"
+ "_adoptPendingConfigDataWithCompletion:"
+ "_configAdoptionWork"
+ "_pendingConfigData"
+ "cancelled while trying to rebuild feed item dropbox, name=%{public}s"
+ "com.apple.newsd.feedItemPool.refresh"
+ "com.apple.newsd.todayFeed.adoptConfig"
+ "configAdoptionWork"
+ "initWithIdentifier:priority:work:"
+ "pendingConfigData"
+ "refreshWork"
+ "removeItemAtURL:error:"
+ "setNeedsRun"
+ "setPendingConfigData:"
- "TodayFeedService did enter operation queue (instance=%{public}@)"
- "TodayFeedService will enter operation queue (instance=%{public}@)"
- "TodayFeedService will reject donated config due to low-data mode"
- "TodayFeedService will reject donated config due to low-power mode"
- "_canAdoptFeedConfig"
- "_keepAliveTokenForInstanceID:"
- "activeRefreshTask"
- "already kicked off a rebuild for all feed item dropboxes"
- "com.apple.newsd.FeedItemPoolRefresh"
- "com.apple.newsd.today-feed.adoptNewConfig-%@"
- "refreshPriority"
```
