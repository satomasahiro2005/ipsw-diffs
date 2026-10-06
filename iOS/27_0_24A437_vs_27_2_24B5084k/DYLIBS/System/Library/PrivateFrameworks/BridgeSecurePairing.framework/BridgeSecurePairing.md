## BridgeSecurePairing

> `/System/Library/PrivateFrameworks/BridgeSecurePairing.framework/BridgeSecurePairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3ba4c` | `0x3d604` | **`+0x1bb8`** |
| `__TEXT.__oslogstring` | `0xded` | `0xf5d` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x3ef8` | `0x4020` | **`+0x128`** |
| `__TEXT.__swift5_reflstr` | `0x669` | `0x699` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x1410` | `0x1440` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x650` | `0x670` | **`+0x20`** |
| `__TEXT.__const` | `0x1988` | `0x19a8` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x4f4` | `0x50c` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x958` | `0x968` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x3d0` | `0x3dc` | **`+0xc`** |
| `__AUTH.__data` | `0x5a8` | `0x5b0` | **`+0x8`** |
| `__DATA.__data` | `0x668` | `0x670` | **`+0x8`** |
| `__TEXT.__swift_as_ret` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x16c` | `0x170` | **`+0x4`** |

### Other Changes

```diff

-1359.9.0.0.0
+1370.0.0.0.0

-  Functions: 837
-  Symbols:   345
-  CStrings:  89
+  Functions: 844
+  Symbols:   347
+  CStrings:  95
Symbols:
+ ___swift_closure_destructor.101Tm
+ ___swift_closure_destructor.66Tm
+ _swift_release_n
- ___swift_closure_destructor.64Tm
CStrings:
+ "Cancelling secure pairing at the local client's request"
+ "Pairing session cancelled locally (reason: %s)"
+ "Pairing was cancelled locally — skipping retry decision"
+ "Secure pairing cancelled locally — not retrying"
+ "Secure pairing session cancelled"
+ "cancel: no pairing in flight (isPairing: %{bool}d, didCancelLocally: %{bool}d)"
```
