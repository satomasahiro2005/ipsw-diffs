## libIPTelephony.dylib

> `/System/Library/PrivateFrameworks/IPTelephony.framework/Support/libIPTelephony.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ab92c` | `0x4abc04` | **`+0x2d8`** |
| `__TEXT.__oslogstring` | `0x4cd37` | `0x4cdca` | **`+0x93`** |
| `__TEXT.__cstring` | `0x140b7` | `0x14117` | **`+0x60`** |
| `__TEXT.__gcc_except_tab` | `0x41ec8` | `0x41f00` | **`+0x38`** |
| `__DATA.__common` | `0xa8` | `0xc0` | **`+0x18`** |
| `__TEXT.__init_offsets` | `0x1a4` | `0x1a8` | **`+0x4`** |

### Other Changes

```diff

-2764.0.0.0.0
+2765.0.0.0.0

-  Functions: 16438
-  Symbols:   24907
-  CStrings:  8702
+  Functions: 16439
+  Symbols:   24910
+  CStrings:  8704
Symbols:
+ __GLOBAL__sub_I_SipRegistrationMetrics.cpp
+ __ZN22SipRegistrationMetrics39kReasonIPSecCompletionEnforcementFailedE
+ __ZN9ImsResultlsIA68_cEERS_RKT_
Functions:
~ __ZN13LazuliSession19handleInviteFailureEjRKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEERK6SipUrijN3xpc5arrayE : 7860 -> 7972
~ __ZN21SipRegistrationClient14handleResponseENSt3__110shared_ptrIK11SipResponseEENS1_I20SipClientTransactionEE : 4912 -> 5428
+ __GLOBAL__sub_I_SipRegistrationMetrics.cpp
~ __ZN9SipDialog19cancelInviteRequestENSt3__110shared_ptrI20SipClientTransactionEEPK24ImsCallTerminationReason : 1232 -> 1204
CStrings:
+ "#W %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored. Will retry Registration."
+ "%{private, mask.hash}sreceived Reg 200 OK. EnableIPSec: %{bool}d, Enforce IPSec: %{bool}d, DefaultTransportGroup: %p, RecvTransportGroup: %p, isEmergency: %{bool}d"
+ "IPSec completion enforcement: 200 OK on insecure transport rejected"
+ "IPSecCompletionEnforcementFailed"
- "#W %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored."
- "%{private, mask.hash}sreceived Reg 200 OK"
```
