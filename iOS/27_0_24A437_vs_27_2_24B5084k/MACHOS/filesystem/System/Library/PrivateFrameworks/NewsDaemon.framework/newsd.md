## newsd

> `/System/Library/PrivateFrameworks/NewsDaemon.framework/newsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54230` | `0x54860` | **`+0x630`** |
| `__TEXT.__cstring` | `0x2b61` | `0x2a81` | **`-0xe0`** |
| `__TEXT.__objc_stubs` | `0x42a0` | `0x4360` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x27cd` | `0x288d` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x218` | `0x2c0` | **`+0xa8`** |
| `__DATA_CONST.__const` | `0x25c0` | `0x2658` | **`+0x98`** |
| `__TEXT.__eh_frame` | `0x2760` | `0x26e0` | **`-0x80`** |
| `__TEXT.__objc_methname` | `0x5f25` | `0x5f95` | **`+0x70`** |
| `__DATA_CONST.__cfstring` | `0x4c0` | `0x480` | **`-0x40`** |
| `__TEXT.__unwind_info` | `0x1418` | `0x1458` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1a08` | `0x1a40` | **`+0x38`** |
| `__DATA.__objc_selrefs` | `0x15c8` | `0x15f8` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x1b8` | `0x1d0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x22b0` | `0x22a0` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x1168` | `0x1160` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5934.3.0.0.0
+5960.0.0.0.0

-  Functions: 1474
-  Symbols:   976
-  CStrings:  1527
+  Functions: 1483
+  Symbols:   975
+  CStrings:  1532
Symbols:
+ _$s10NewsDaemon29ProxyScoringServiceConnectionC13InterestTokenC10invalidateyyF
+ _$s10NewsDaemon29ProxyScoringServiceConnectionC13interestTokenAC08InterestH0CyF
- _$s10NewsDaemon29ProxyScoringServiceConnectionC11popInterestyyF
- _$s10NewsDaemon29ProxyScoringServiceConnectionC12pushInterestyyF
- _objc_retain_x28
CStrings:
+ "T@\"<NDDownloadConsumer>\",&,N,V_consumer"
+ "TB,N,GisInvalidated,V_invalidated"
+ "_invalidated"
+ "_sendPersistedArchivesToConsumerForRequest:"
+ "connectionDidInvalidate:"
+ "consumer proxy invalidated, draining %lu messages, connection=%{public}@"
+ "consumer proxy lost connection, will drain %lu messages, connection=%{public}@"
+ "ignoring consumer=%p registered outside of an XPC connection"
+ "isConnectedTo:"
+ "isInvalidated"
+ "removeAllObjects"
+ "setConsumer:"
+ "setInvalidated:"
+ "tearing down consumer=%p after its connection went away"
- "-[NDContentDownloadService registerDownloadConsumer:]_block_invoke"
- "-[NDContentDownloadService setCurrentConnection:]"
- "T@\"<NDDownloadConsumer>\",R,N,V_consumer"
- "T@\"NSXPCConnection\",W,N,V_currentConnection"
- "_currentConnection"
- "consumer proxy lost connection, will drop %lu messages, connection=%{public}@"
- "registering a consumer without an XPC connection"
- "replacing XPC connection while a consumer is already active"
- "setCurrentConnection:"
```
