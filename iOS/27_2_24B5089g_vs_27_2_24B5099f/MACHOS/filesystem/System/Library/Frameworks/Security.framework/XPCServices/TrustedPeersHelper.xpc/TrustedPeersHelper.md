## TrustedPeersHelper

> `/System/Library/Frameworks/Security.framework/XPCServices/TrustedPeersHelper.xpc/TrustedPeersHelper`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b0e04` | `0x2b543c` | **`+0x4638`** |
| `__TEXT.__oslogstring` | `0xe35b` | `0xe68b` | **`+0x330`** |
| `__DATA_CONST.__const` | `0x15368` | `0x15520` | **`+0x1b8`** |
| `__TEXT.__cstring` | `0x17e20` | `0x17f90` | **`+0x170`** |
| `__TEXT.__eh_frame` | `0x8028` | `0x8130` | **`+0x108`** |
| `__TEXT.__swift5_capture` | `0x53fc` | `0x54b4` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x92d1` | `0x9351` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x5028` | `0x50a0` | **`+0x78`** |
| `__TEXT.__objc_stubs` | `0x61a0` | `0x61e0` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x24b0` | `0x24e0` | **`+0x30`** |
| `__DATA_CONST.__got` | `0xad8` | `0xaf8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x40aa` | `0x40ca` | **`+0x20`** |
| `__DATA.__objc_const` | `0x7080` | `0x7098` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x1f10` | `0x1f28` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x1268` | `0x1280` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x2954` | `0x2968` | **`+0x14`** |
| `__TEXT.__const` | `0xd750` | `0xd760` | **`+0x10`** |
| `__DATA.__data` | `0x85c8` | `0x85d0` | **`+0x8`** |
| `__TEXT.__constg_swiftt` | `0x3cf4` | `0x3cfc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-62460.40.56.502.1
+62460.40.74.0.0

-  Functions: 9011
-  Symbols:   594
-  CStrings:  3269
+  Functions: 9059
+  Symbols:   596
+  CStrings:  3285
Symbols:
+ _kSecurityRTCEventNameTDLTDIDReapperance
+ _kSecurityRTCFieldMIDRolled
CStrings:
+ "Failed to save observed ego stable ID history: %{public}s"
+ "This device's new TDID matches one it has used before"
+ "Trusted peer's machine ID rolled, and the TDID changed to a different value"
+ "Trusted peer's machine ID rolled, and the TDID did not survive the roll"
+ "Trusted peer's machine ID rolled; the TDID was never present, either before or after"
+ "captureTDIDStabilityTelemetry: thisDeviceMachineID=%{public}s cachedMachineID=%{public}s resolvedMachineID=%{public}s existingStableID=%{public}s incomingStableID=%{public}s egoPairFound=%{bool,public}d midRolled=%{bool,public}d"
+ "checkEgoStableIDUniqueness: machineID=%{public}s candidate=%{public}s historyCount=%{public}ld tdidMatches=%{public}ld reused=%{bool,public}d midRolled=%{bool,public}d"
+ "notifyPeerTrustEstablished"
+ "notifyPeerTrustEstablished complete: %{public}s"
+ "notifyPeerTrustEstablished failed for %{public}s: %{public}s"
+ "notifyPeerTrustEstablished for %{public}s"
+ "notifyPeerTrustEstablished(reply:)"
+ "notifyPeerTrustEstablished: Octagon confirmed trust, submitting ego stable trusted device ID: %{public}s machineID: %{public}s"
+ "notifyPeerTrustEstablishedWithSpecificUser:reply:"
+ "observedEgoTrustedDeviceIDs"
+ "recordEgoStableIDIntoHistory: already present, not updating cache"
+ "recordEgoStableIDIntoHistory: cache updated, now containing %{public}ld entries"
+ "setObservedEgoTrustedDeviceIDs:"
- "Trusted peer's TDID is stable"
- "captureTDIDStabilityTelemetry: machineID=%{public}s existingStableID=%{public}s incomingStableID=%{public}s"
```
