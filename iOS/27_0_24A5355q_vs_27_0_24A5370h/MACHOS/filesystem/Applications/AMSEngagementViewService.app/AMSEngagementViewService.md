## AMSEngagementViewService

> `/Applications/AMSEngagementViewService.app/AMSEngagementViewService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x115d0` | `0x12958` | **`+0x1388`** |
| `__TEXT.__eh_frame` | `0x118` | `0x640` | **`+0x528`** |
| `__DATA_CONST.__const` | `0x7e0` | `0x8f8` | **`+0x118`** |
| `__TEXT.__unwind_info` | `0x490` | `0x598` | **`+0x108`** |
| `__TEXT.__cstring` | `0xa56` | `0x986` | **`-0xd0`** |
| `__TEXT.__const` | `0xb34` | `0xbc4` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x56a` | `0x5ea` | **`+0x80`** |
| `__TEXT.__swift5_capture` | `0x1a4` | `0x21c` | **`+0x78`** |
| `__TEXT.__objc_methtype` | `0xeed` | `0xf4d` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0xed0` | `0xf20` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `—` | `0x38` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x770` | `0x798` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `—` | `0x24` | **`+0x24`** |
| `__TEXT.__swift_as_entry` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA.__data` | `0x978` | `0x988` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x1cbd` | `0x1ccd` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x1c0` | `0x1c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-8.0.35.2.1
+8.0.38.0.0

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 508
-  Symbols:   418
-  CStrings:  443
+  Functions: 569
+  Symbols:   422
+  CStrings:  441
Symbols:
+ _$sScA15unownedExecutorScevgTj
+ _$sScM6sharedScMvgZ
+ _$sScMMa
+ _$sScMScAsWP
+ _$sScP8rawValues5UInt8Vvg
+ _$sScPMa
+ _$ss5ErrorWS
+ _$sytN
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_continuation_throwingResume
+ _swift_continuation_throwingResumeWithError
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
- _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
- _$s10Foundation3URLV4hostSSSgvg
- _$s10Foundation3URLV6stringACSgSSh_tcfC
- _$s10Foundation3URLVSQAAMc
- _$sSQ2eeoiySbx_xtFZTj
- _$sSS10lowercasedSSyF
- _$sSy10FoundationE8containsySbqd__SyRd__lF
- _$ss20__StaticArrayStorageCN
- ___stack_chk_fail
- ___stack_chk_guard
- __swiftImmortalRefCount
- _swift_bridgeObjectRelease_n
CStrings:
+ "initWithBag:"
+ "resultWithTimeout:completion:"
+ "v24@?0@\"AMSEngagementEnqueueResult\"8@\"NSError\"16"
+ "v24@?0@\"NSDictionary\"8@\"NSError\"16"
- "Failed to encode URL: "
- "Tried to build falback URL from unsupported url"
- "promiseWithTimeout:"
- "resultWithError:"
- "settings-navigation://com.apple.Settings.AMS"
- "settings-navigation://com.apple.Settings.AppleAccount/ICLOUD_SERVICE"
```
