## SeymourServicesCore

> `/System/Library/PrivateFrameworks/SeymourServicesCore.framework/SeymourServicesCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5f538` | `0x60b48` | **`+0x1610`** |
| `__TEXT.__oslogstring` | `0x210d` | `0x22dd` | **`+0x1d0`** |
| `__AUTH_CONST.__const` | `0x3788` | `0x3800` | **`+0x78`** |
| `__TEXT.__swift5_capture` | `0x8d4` | `0x91c` | **`+0x48`** |
| `__AUTH_CONST.__auth_got` | `0xf38` | `0xf60` | **`+0x28`** |
| `__DATA.__data` | `0x9b8` | `0x9e0` | **`+0x28`** |
| `__TEXT.__swift5_typeref` | `0x1b92` | `0x1bb6` | **`+0x24`** |
| `__DATA_DIRTY.__data` | `0x14e8` | `0x14d8` | **`-0x10`** |
| `__TEXT.__const` | `0x4c40` | `0x4c50` | **`+0x10`** |
| `__TEXT.__cstring` | `0xc53` | `0xc63` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x14ec` | `0x14f4` | **`+0x8`** |
| `__TEXT.__eh_frame` | `0x3c58` | `0x3c5c` | **`+0x4`** |

### Other Changes

```diff

-2027.1.54.0.0
+2027.1.63.0.0

-  Functions: 1995
-  Symbols:   847
-  CStrings:  200
+  Functions: 2000
+  Symbols:   849
+  CStrings:  205
Symbols:
+ ___swift_closure_destructor.44Tm
+ ___swift_closure_destructorTm
+ _objc_retain_x24
+ _symbolic SS7voucher_______p4link_____4roleSDySSSo21RPCompanionLinkDeviceCG11heldDevices______p15expirationTimer______pSg26aggressiveBluetoothScanner_____y______G12continuationt 19SeymourServicesCore11RapportLinkP 0aC021RemoteParticipantRoleO So24OS_dispatch_source_timerP AA27AggressiveBluetoothScanningP ScS12ContinuationV AA0fG14DiscoveryEventO
+ _symbolic SS7voucher_______p4link_____4roleSDySSSo21RPCompanionLinkDeviceCG17discoveredDevices______p15expirationTimer______pSg26aggressiveBluetoothScanner_____y______G12continuationt 19SeymourServicesCore11RapportLinkP 0aC021RemoteParticipantRoleO So24OS_dispatch_source_timerP AA27AggressiveBluetoothScanningP ScS12ContinuationV AA0fG14DiscoveryEventO
- ___swift_closure_destructor.25Tm
- _symbolic SS10identifier_______p4link_____4roleSDySSSo21RPCompanionLinkDeviceCG17discoveredDevices______p15expirationTimer______pSg26aggressiveBluetoothScanner_____y______G12continuationt 19SeymourServicesCore11RapportLinkP 0aC021RemoteParticipantRoleO So24OS_dispatch_source_timerP AA27AggressiveBluetoothScanningP ScS12ContinuationV AA0fG14DiscoveryEventO
- _symbolic SS10identifier_______p4link_____4role______p15expirationTimer______pSg26aggressiveBluetoothScanner_____y______G12continuationt 19SeymourServicesCore11RapportLinkP 0aC021RemoteParticipantRoleO So24OS_dispatch_source_timerP AA27AggressiveBluetoothScanningP ScS12ContinuationV AA0fG14DiscoveryEventO
CStrings:
+ "Changed device for inactive or stale discovery (%{public}s): %{public}@"
+ "Clobbering existing discovery for voucher: %{public}s"
+ "Discovered device for inactive or stale discovery (%{public}s): %{public}@"
+ "Draining %{public}ld device(s) reported while activating"
+ "Ending discovery while activating, discarding %{public}ld held device(s)"
+ "Holding changed device reported while activating: %{public}@"
+ "Holding device reported while activating: %{public}@"
+ "Lost device for inactive or stale discovery (%{public}s): %{public}@"
+ "Refreshing already discovered participant (%{public}s): %{public}s"
+ "Registering discovered participant (%{public}s): %{public}s"
+ "Releasing device held while activating, now lost: %{public}@"
+ "voucher link role discoveredDevices expirationTimer aggressiveBluetoothScanner continuation "
+ "voucher link role heldDevices expirationTimer aggressiveBluetoothScanner continuation "
- "Changed device while inactive: %{public}@"
- "Clobbering existing discovery for identifier: %{public}s"
- "Discovered device while inactive: %{public}@"
- "Ending discovery while activating"
- "Lost device while inactive: %{public}@"
- "Registering discovered participant (%{public}s: %{public}s"
- "identifier link role discoveredDevices expirationTimer aggressiveBluetoothScanner continuation "
- "identifier link role expirationTimer aggressiveBluetoothScanner continuation "
```
