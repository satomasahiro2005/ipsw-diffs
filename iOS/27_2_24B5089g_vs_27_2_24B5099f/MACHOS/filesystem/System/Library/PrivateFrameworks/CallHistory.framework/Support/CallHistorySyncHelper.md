## CallHistorySyncHelper

> `/System/Library/PrivateFrameworks/CallHistory.framework/Support/CallHistorySyncHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x409a0` | `0x40ba8` | **`+0x208`** |
| `__TEXT.__objc_methname` | `0x7a73` | `0x7b93` | **`+0x120`** |
| `__TEXT.__objc_stubs` | `0x62a0` | `0x6360` | **`+0xc0`** |
| `__DATA.__objc_selrefs` | `0x1f98` | `0x1fc8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x580` | `0x588` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe60` | `0xe68` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-156.200.88.2.3
+156.200.120.0.0

-  Functions: 1395
-  Symbols:   644
-  CStrings:  2169
+  Functions: 1396
+  Symbols:   645
+  CStrings:  2175
Symbols:
+ _OBJC_CLASS_$_INCallRecord
Functions:
~ sub_10000fc60 : 2628 -> 2612
+ sub_1000114d0
CStrings:
+ "callerIdIsBlocked"
+ "initWithCallRecordFilter:callRecordToCallBack:audioRoute:destinationType:contacts:callCapability:"
+ "initWithIdentifier:dateCreated:callRecordType:callCapability:callDuration:unseen:participants:numberOfCalls:isCallerIdBlocked:"
+ "numberOfOccurrences"
+ "setPreferredCallProvider:"
+ "setTTYType:"
```
