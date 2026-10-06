## TCCAuthorizationService

> `/System/Library/PrivateFrameworks/TCCAuthorizationService.framework/TCCAuthorizationService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x12904` | `0x16970` | **`+0x406c`** |
| `__TEXT.__eh_frame` | `0x290` | `0x690` | **`+0x400`** |
| `__TEXT.__const` | `0xfc0` | `0x11a0` | **`+0x1e0`** |
| `__AUTH.__data` | `0x430` | `0x550` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x498` | `0x5a8` | **`+0x110`** |
| `__TEXT.__constg_swiftt` | `0x84c` | `0x928` | **`+0xdc`** |
| `__DATA.__bss` | `0x1400` | `0x14a0` | **`+0xa0`** |
| `__AUTH_CONST.__auth_got` | `0x6a8` | `0x738` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x1410` | `0x14a0` | **`+0x90`** |
| `__TEXT.__swift5_reflstr` | `0x3a3` | `0x423` | **`+0x80`** |
| `__AUTH_CONST.__const` | `0xb60` | `0xae8` | **`-0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x498` | `0x500` | **`+0x68`** |
| `__TEXT.__swift5_capture` | `0x16c` | `0x118` | **`-0x54`** |
| `__AUTH.__objc_data` | `0xd80` | `0xdd0` | **`+0x50`** |
| `__DATA.__data` | `0x720` | `0x770` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x51c` | `0x54e` | **`+0x32`** |
| `__TEXT.__cstring` | `0x1017` | `0xfe7` | **`-0x30`** |
| `__TEXT.__swift_as_cont` | `—` | `0x28` | **`+0x28`** |
| `__TEXT.__swift_as_ret` | `—` | `0x20` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `—` | `0x1c` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x60` | `0x68` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x70` | `0x78` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xa0` | `0xa4` | **`+0x4`** |

### Other Changes

```diff

-906.0.0.0.0
+909.0.0.0.0

+  - /usr/lib/swift/libswiftObservation.dylib

+  - /usr/lib/swift/libswift_Concurrency.dylib

-  Functions: 554
-  Symbols:   442
+  Functions: 592
+  Symbols:   460
Symbols:
+ __DATA__TtC23TCCAuthorizationServiceP33_8F7FB710C4FFAE46FD23FFD3591141FE25AuthorizationRecordBuffer
+ __IVARS__TtC23TCCAuthorizationServiceP33_8F7FB710C4FFAE46FD23FFD3591141FE25AuthorizationRecordBuffer
+ __METACLASS_DATA__TtC23TCCAuthorizationServiceP33_8F7FB710C4FFAE46FD23FFD3591141FE25AuthorizationRecordBuffer
+ ___swift_async_cont_functlets
+ ___swift_async_entry_functlets
+ ___swift_async_ret_functlets
+ ___swift_memcpy19_8
+ __swift_implicitisolationactor_to_executor_cast
+ _free
+ _objc_retain_x28
+ _swift_continuation_await
+ _swift_continuation_init
+ _swift_coroFrameAlloc
+ _swift_errorRetain
+ _swift_getKeyPath
+ _swift_retain_x25
+ _swift_task_alloc
+ _swift_task_create
+ _swift_task_dealloc
+ _swift_task_switch
+ _symbolic Say_____G 23TCCAuthorizationService27AuthorizationRecordSnapshot33_8F7FB710C4FFAE46FD23FFD3591141FELLV
+ _symbolic SayypGSg
+ _symbolic ScA_pSg
+ _symbolic ScCySay_____G_____G 23TCCAuthorizationService27AuthorizationRecordSnapshot33_8F7FB710C4FFAE46FD23FFD3591141FELLV s5NeverO
+ _symbolic ScCySayypGSg______pG s5ErrorP
+ _symbolic ScPSg
+ _symbolic _____ 11Observation0A9RegistrarV
+ _symbolic _____ 23TCCAuthorizationService25AuthorizationRecordBuffer33_8F7FB710C4FFAE46FD23FFD3591141FELLC
+ _symbolic _____ 23TCCAuthorizationService27AuthorizationRecordSnapshot33_8F7FB710C4FFAE46FD23FFD3591141FELLV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 23TCCAuthorizationService27AuthorizationRecordSnapshot33_8F7FB710C4FFAE46FD23FFD3591141FELLV
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
+ _type_layout_string 23TCCAuthorizationService27AuthorizationRecordSnapshot33_8F7FB710C4FFAE46FD23FFD3591141FELLV
- ___swift_closure_destructor.10Tm
- ___swift_closure_destructor.22Tm
- _dispatch_queue_get_label
- _swift_release_x27
- _swift_retain_x23
- _swift_unownedRelease
- _swift_unownedRetain
- _swift_unownedRetainStrong
- _swift_willThrowTypedImpl
- _symbolic SaySSGz_Xx
- _symbolic Say_____G 8Dispatch0A13WorkItemFlagsV
- _symbolic So29MOAppTCCDefaultsConfigurationC
- _symbolic _____Xo 23TCCAuthorizationService18ManagedTCCDefaultsC
- _symbolic _____z_Xx 23TCCAuthorizationService07ManagedB0C13AuthorizationO
- _tcc_authorization_record_get_admin_override_value
CStrings:
+ "collectAuthorizationRecords()"
+ "currentLocalNetworkAuthorization()"
+ "fullSheetPrompt"
- "#ManagedTCCDefaults received TCCService: "
- "#ManagedTCCDefaults received non-TCCService: "
- "#ManagedTCCDefaults received the record"
```
