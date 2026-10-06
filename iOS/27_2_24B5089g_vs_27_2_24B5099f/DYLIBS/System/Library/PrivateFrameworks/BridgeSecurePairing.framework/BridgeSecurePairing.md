## BridgeSecurePairing

> `/System/Library/PrivateFrameworks/BridgeSecurePairing.framework/BridgeSecurePairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d604` | `0x40e3c` | **`+0x3838`** |
| `__TEXT.__eh_frame` | `0x4020` | `0x44c0` | **`+0x4a0`** |
| `__TEXT.__unwind_info` | `0x1440` | `0x1578` | **`+0x138`** |
| `__AUTH_CONST.__const` | `0xc90` | `0xd80` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0xf5d` | `0x103d` | **`+0xe0`** |
| `__TEXT.__const` | `0x19a8` | `0x1a60` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x670` | `0x710` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x320` | `0x3a4` | **`+0x84`** |
| `__TEXT.__swift_as_cont` | `0x3dc` | `0x440` | **`+0x64`** |
| `__TEXT.__swift5_reflstr` | `0x699` | `0x6f9` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x50c` | `0x560` | **`+0x54`** |
| `__TEXT.__swift5_typeref` | `0x899` | `0x8e9` | **`+0x50`** |
| `__AUTH.__data` | `0x5b0` | `0x5f8` | **`+0x48`** |
| `__TEXT.__swift_as_entry` | `0x170` | `0x19c` | **`+0x2c`** |
| `__TEXT.__swift_as_ret` | `0x1c0` | `0x1ec` | **`+0x2c`** |
| `__DATA.__data` | `0x670` | `0x698` | **`+0x28`** |
| `__AUTH_CONST.__auth_got` | `0x968` | `0x988` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x46c` | `0x48c` | **`+0x20`** |

### Other Changes

```diff

-1372.0.0.0.0
+1377.1.0.0.0

-  Functions: 844
-  Symbols:   347
-  CStrings:  95
+  Functions: 906
+  Symbols:   355
+  CStrings:  99
Symbols:
+ ___swift_closure_destructor.102Tm
+ ___swift_closure_destructor.10Tm
+ ___swift_closure_destructor.110Tm
+ ___swift_closure_destructor.114Tm
+ ___swift_closure_destructor.67Tm
+ _objc_release_x26
+ _swift_release_x9
+ _swift_task_future_wait_throwing
+ _symbolic ScTy___________pGSg 7Network10NWEndpointO s5ErrorP
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 7Network10NWEndpointO s5ErrorP
+ _symbolic _____y___________pGSg s6ResultOsRi_zRi0_zrlE 7Network10NWEndpointO s5ErrorP
+ _symbolic ytSg
+ _symbolic ytSgIeAgHr_
- ___swift_closure_destructor.101Tm
- ___swift_closure_destructor.103Tm
- ___swift_closure_destructor.66Tm
- ___swift_closure_destructor.88Tm
- _swift_conformsToProtocol2
CStrings:
+ "BridgeSecurePairingServerConnection deinit"
+ "Failed to notify remote of abort: %@"
+ "Invalidating session actor while waiting for a client: %@"
+ "Pairing state stream ended without reaching a terminal state"
+ "Secure pairing connect was cancelled locally — abandoning"
- "Failed to notify remote of abort after paused-state failure: %@"
```
