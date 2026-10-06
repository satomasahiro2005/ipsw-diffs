## CallHistorySyncHelper

> `/System/Library/PrivateFrameworks/CallHistory.framework/Support/CallHistorySyncHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4063c` | `0x40830` | **`+0x1f4`** |
| `__TEXT.__oslogstring` | `0x52b6` | `0x5396` | **`+0xe0`** |
| `__DATA.__objc_const` | `0x5c00` | `0x5c20` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1c00` | `0x1c20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x7a63` | `0x7a73` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x588` | `0x580` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0x220` | `0x224` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-145.100.7.2.1
+147.100.5.2.1

-  Functions: 1393
-  Symbols:   645
-  CStrings:  2163
+  Functions: 1395
+  Symbols:   644
+  CStrings:  2167
Symbols:
- _kCallUpdatePropertyRead
CStrings:
+ "Calling back with message %{public}@"
+ "Fetch requested while sync in progress; will run another fetch once the current one finishes"
+ "Pending fetch changes result (%{public}@) message (%{public}@)"
+ "Pending fetch was requested during the previous sync; starting it now"
+ "_pendingFetch"
- "Calling back with result %{public}@"
```
