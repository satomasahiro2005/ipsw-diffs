## DistributedTimersDaemon

> `/System/Library/PrivateFrameworks/DistributedTimersDaemon.framework/DistributedTimersDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8e580` | `0x8e760` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x15a0` | `0x1710` | **`+0x170`** |
| `__AUTH_CONST.__const` | `0x25d8` | `0x26b8` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x2091` | `0x2151` | **`+0xc0`** |
| `__TEXT.__eh_frame` | `0x4c70` | `0x4cf0` | **`+0x80`** |
| `__AUTH.__objc_data` | `0x320` | `0x378` | **`+0x58`** |
| `__AUTH.__data` | `0xbf0` | `0xba0` | **`-0x50`** |
| `__DATA.__data` | `0x1160` | `0x11b0` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x9a4` | `0x9d8` | **`+0x34`** |
| `__TEXT.__swift5_reflstr` | `0x899` | `0x8c9` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x10b8` | `0x10e0` | **`+0x28`** |
| `__TEXT.__swift5_fieldmd` | `0xa50` | `0xa74` | **`+0x24`** |
| `__TEXT.__cstring` | `0x935` | `0x955` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x804` | `0x818` | **`+0x14`** |
| `__TEXT.__swift5_typeref` | `0xea8` | `0xeba` | **`+0x12`** |
| `__TEXT.__unwind_info` | `0x1990` | `0x19a0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3b8` | `0x3c4` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x50` | `0x58` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x1a0` | `0x1a4` | **`+0x4`** |

### Other Changes

```diff

-524.0.16.0.0
+524.0.26.0.0

-  Functions: 1797
-  Symbols:   696
-  CStrings:  271
+  Functions: 1807
+  Symbols:   706
+  CStrings:  275
Symbols:
+ __DATA__TtCC23DistributedTimersDaemon17DTTransportDaemonP33_D0772C63A9128FD93A891935DD2DF83A22DTOperationItemRequest
+ __IVARS__TtCC23DistributedTimersDaemon17DTTransportDaemonP33_D0772C63A9128FD93A891935DD2DF83A22DTOperationItemRequest
+ __METACLASS_DATA__TtCC23DistributedTimersDaemon17DTTransportDaemonP33_D0772C63A9128FD93A891935DD2DF83A22DTOperationItemRequest
+ ___swift_assignWithCopy_strong
+ ___swift_assignWithTake_strong
+ ___swift_closure_destructor.156Tm
+ ___swift_closure_destructor.163Tm
+ ___swift_closure_destructor.175Tm
+ ___swift_closure_destructor.196Tm
+ ___swift_destroy_strong
+ ___swift_initWithCopy_strong
+ ___swift_memcpy8_8
+ _swift_release_x9
+ _symbolic _____ 23DistributedTimersDaemon011DTTransportC0C22DTOperationItemRequest33_D0772C63A9128FD93A891935DD2DF83ALLC
+ _symbolic _____Sg 14CoreUtilsSwift7CUTimerC
+ _symbolic _____SgXw 23DistributedTimersDaemon011DTTransportC0C22DTOperationItemRequest33_D0772C63A9128FD93A891935DD2DF83ALLC
+ _symbolic _____SgXwz_Xx 23DistributedTimersDaemon011DTTransportC0C22DTOperationItemRequest33_D0772C63A9128FD93A891935DD2DF83ALLC
+ _type_layout_string 23DistributedTimersDaemon011DTTransportC0C15DTOperationItem33_D0772C63A9128FD93A891935DD2DF83ALLO
- ___swift_closure_destructor.166Tm
- ___swift_closure_destructor.178Tm
- ___swift_closure_destructor.199Tm
- ___swift_get_extra_inhabitant_indexTm
- ___swift_store_extra_inhabitant_indexTm
- _swift_cvw_initEnumMetadataSingleCaseWithLayoutString
- _symbolic _____ 23DistributedTimersDaemon011DTTransportC0C22DTOperationItemRequest33_D0772C63A9128FD93A891935DD2DF83ALLV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 23DistributedTimersDaemon011DTTransportF0C15DTOperationItem33_D0772C63A9128FD93A891935DD2DF83ALLO
CStrings:
+ "### Operation timeout: xid=%s, request=%s"
+ "Operation enqueue: xid=%s, request=%s, timeout=%s"
+ "Operation timed out"
+ "removeAlarm: not found, treating as removed: %@, %s"
+ "removeTimer: not found, treating as removed: %@, %s"
- "Operation enqueue: xid=%s, request=%s"
```
