## ProximityReaderDaemon

> `/System/Library/PrivateFrameworks/ProximityReaderDaemon.framework/ProximityReaderDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x213c40` | `0x2157e4` | **`+0x1ba4`** |
| `__TEXT.__oslogstring` | `0xc9cb` | `0xcb3b` | **`+0x170`** |
| `__DATA_DIRTY.__bss` | `0x2d8` | `0x3d8` | **`+0x100`** |
| `__DATA.__bss` | `0x12c90` | `0x12ba0` | **`-0xf0`** |
| `__TEXT.__eh_frame` | `0xeb40` | `0xec1c` | **`+0xdc`** |
| `__TEXT.__swift5_capture` | `0x3440` | `0x34e4` | **`+0xa4`** |
| `__AUTH_CONST.__objc_const` | `0x7ee8` | `0x7f48` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x5103` | `0x5163` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x6280` | `0x62e0` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0xe7a0` | `0xe7f0` | **`+0x50`** |
| `__TEXT.__const` | `0xe7e4` | `0xe834` | **`+0x50`** |
| `__AUTH_CONST.__auth_got` | `0x32f8` | `0x3330` | **`+0x38`** |
| `__TEXT.__swift5_fieldmd` | `0x59a4` | `0x59c8` | **`+0x24`** |
| `__AUTH.__data` | `0x5fb8` | `0x5fd8` | **`+0x20`** |
| `__DATA.__data` | `0x2278` | `0x2288` | **`+0x10`** |
| `__AUTH.__objc_data` | `0x1328` | `0x1330` | **`+0x8`** |
| `__DATA.__common` | `0x540` | `0x548` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xda8` | `0xdb0` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x118` | `0x120` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0xb98` | `0xba0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x5a4` | `0x5a8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x624` | `0x628` | **`+0x4`** |

### Other Changes

```diff

-151.2.0.0.0
+151.5.0.0.0

-  Functions: 7068
-  Symbols:   2552
-  CStrings:  1680
+  Functions: 7094
+  Symbols:   2553
+  CStrings:  1684
Symbols:
+ ___swift_closure_destructor.148Tm
+ ___swift_closure_destructor.14Tm
+ ___swift_closure_destructor.174Tm
+ ___swift_closure_destructor.24Tm
+ ___swift_closure_destructor.281Tm
+ ___swift_closure_destructor.35Tm
+ ___swift_closure_destructor.44Tm
+ ___swift_closure_destructor.53Tm
+ ___swift_closure_destructor.74Tm
+ ___swift_exist.box.addr_destructor.191Tm
- ___swift_closure_destructor.135Tm
- ___swift_closure_destructor.22Tm
- ___swift_closure_destructor.276Tm
- ___swift_closure_destructor.31Tm
- ___swift_closure_destructor.36Tm
- ___swift_closure_destructor.45Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.72Tm
- ___swift_exist.box.addr_destructor.187Tm
CStrings:
+ "Allowing %{public}s to connect"
+ "CorePeerConnectionDelegate: pairing no longer in flight, restoring NFC retry hint"
+ "CorePeerConnectionDelegate: pairing started, cancelling NFC retry hint"
+ "CorePeerSubscriberDelegate: pairing started"
+ "Customer disconnected from a ready session; live activity will show Customer Ended"
+ "EngagementCustomerService | not authorized: %{public}s"
+ "Websocket %{public}hd: Receive Data Payload: %ld bytes"
+ "Websocket %{public}hd: Send Data Payload: %ld bytes"
- "Allowing %s to connect"
- "EngagementCustomerService | not authorized"
- "Websocket %{public}hd: Receive Data Payload: %s"
- "Websocket %{public}hd: Send Data Payload: %s"
```
