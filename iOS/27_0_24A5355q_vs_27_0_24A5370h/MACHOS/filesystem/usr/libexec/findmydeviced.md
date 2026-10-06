## findmydeviced

> `/usr/libexec/findmydeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4be2a8` | `0x4d2500` | **`+0x14258`** |
| `__TEXT.__eh_frame` | `0x240dc` | `0x2587c` | **`+0x17a0`** |
| `__TEXT.__oslogstring` | `0x1bcc9` | `0x1c339` | **`+0x670`** |
| `__TEXT.__unwind_info` | `0xedb0` | `0xf410` | **`+0x660`** |
| `__DATA_CONST.__const` | `0x1caa0` | `0x1ce50` | **`+0x3b0`** |
| `__TEXT.__const` | `0x452e6` | `0x45586` | **`+0x2a0`** |
| `__TEXT.__swift5_typeref` | `0x4a86` | `0x4c72` | **`+0x1ec`** |
| `__TEXT.__swift5_capture` | `0x1bac` | `0x1d58` | **`+0x1ac`** |
| `__TEXT.__cstring` | `0xdbfe` | `0xdd9e` | **`+0x1a0`** |
| `__TEXT.__swift_as_cont` | `0x1e4c` | `0x1f84` | **`+0x138`** |
| `__DATA.__data` | `0xa938` | `0xaa60` | **`+0x128`** |
| `__TEXT.__swift_as_ret` | `0x1308` | `0x13c0` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x20331` | `0x203c9` | **`+0x98`** |
| `__TEXT.__swift5_reflstr` | `0x541e` | `0x54ae` | **`+0x90`** |
| `__DATA.__bss` | `0x268e0` | `0x26960` | **`+0x80`** |
| `__DATA.__objc_const` | `0x1e6e0` | `0x1e760` | **`+0x80`** |
| `__TEXT.__constg_swiftt` | `0x55bc` | `0x563c` | **`+0x80`** |
| `__TEXT.__swift_as_entry` | `0xcc4` | `0xd30` | **`+0x6c`** |
| `__TEXT.__swift5_fieldmd` | `0x6830` | `0x686c` | **`+0x3c`** |
| `__TEXT.__auth_stubs` | `0x4e20` | `0x4e50` | **`+0x30`** |
| `__DATA_CONST.__cfstring` | `0xb0e0` | `0xb100` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1a80` | `0x1aa0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x2720` | `0x2738` | **`+0x18`** |
| `__DATA_CONST.__auth_ptr` | `0x1e20` | `0x1e28` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x130c` | `0x1310` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-479.30.5.16.3
+481.30.6.7.1

-  Functions: 15839
-  Symbols:   2712
-  CStrings:  10241
+  Functions: 16055
+  Symbols:   2719
+  CStrings:  10279
Symbols:
+ _$s10FindMyBase13WorkItemQueueC10invalidateyyYaFTjTu
+ _$s10FindMyBase2FMO10XPCSessionC10identifier10Foundation4UUIDVvg
+ _$s10FindMyBase2FMO10XPCSessionC10represents20underlyingConnectionSbSo15NSXPCConnectionC_tYaFTjTu
+ _$s19FindMyDaemonSupport23XPCClientConnectionPoolC5countSivgTj
+ _$sST10FindMyBaseE11asyncFilterySay7ElementQzGSbADYaYbKXEYaKF
+ _$sST10FindMyBaseE11asyncFilterySay7ElementQzGSbADYaYbKXEYaKFTu
+ _$sSo15NSXPCConnectionC10FindMyBaseE2id10Foundation4UUIDVvg
+ _$ss6ResultOMn
- _$s19FindMyDaemonSupport23XPCClientConnectionPoolC18setStartProcessingyyyyYaYbcSgFTj
CStrings:
+ "%s Found existing record %{private,mask.hash}s matching identifier %{public}s, skipping serial number fetch."
+ "%s: forcing alreadyInRepair via user default"
+ "%s: objectForSerialNumber returned nil for serial %@"
+ "%{public}s: Already got a HeartBeat monitor"
+ "%{public}s: Canceling task for detectedNearby Heartbeat"
+ "%{public}s: Starting detectedNearby Heartbeat"
+ "%{public}s: Stopping detectedNearby Heartbeat"
+ "%{public}s: error: %@"
+ "AccessoryDiscoveryService."
+ "AccessoryDiscoveryService.disableFindMyPairing failed with error: %@"
+ "AccessoryDiscoveryService.serviceQueue"
+ "Added connection %s (underlyingID='%s'), now has %ld active connections for local findable %{private,mask.hash}s"
+ "BT unpair failed for %{public}s: %{public}@"
+ "Clients no longer active, stopping finding"
+ "Creating per-identifier queue for %{public}s"
+ "Device connect event saving ignoring non-paired peripheral: %{public}s"
+ "Device disconnect event saving ignoring non-paired peripheral: %{public}s"
+ "Event for stop processing, will attempt to stop finding for local findable %{private,mask.hash}s"
+ "Failed to monitor CloudKit state, error: %@"
+ "Failed to store '.connect/.detectedNearby' device event: %{public}@"
+ "Failed to store '.disconnect/.disappeared' device event: %{public}@"
+ "ForceAlreadyInRepairState"
+ "Local-findable accessory %{public}s was deleted, attempting BT unpair"
+ "Monitoring CloudKit state stream for local-findable lifecycle"
+ "Peripheral %{public}s is paired: %{bool}d"
+ "Releasing per-identifier queue for %{public}s"
+ "Removed connection (underlyingID='%s'), now has %ld active connections for local findable %{private,mask.hash}s"
+ "Will attempt to stop finding, no more active clients"
+ "Will attempt to stop finding, regardless of active clients"
+ "Will not attempt to stop finding due to clients still being active"
+ "Will not invalidate, finding still in progress"
+ "Will restart fast advertisement after rediscovery / reconnection"
+ "addConnection(_:)"
+ "detectedNearbyHeartbeatMonitoring"
+ "generation"
+ "invalidate(matchingGeneration:)"
+ "perIdentifierQueueRefCounts"
+ "perIdentifierQueues"
+ "removeConnection(_:)"
+ "runOnIdentifierQueue(_:timeout:_:)"
+ "serialNumberBasedPairingStatus(forPencilIdentifier:macAddress:)"
+ "serviceQueue"
+ "startDetectedNearbyHeartbeat()"
+ "stop(clientXPCConnection:)"
+ "stopDetectedNearbyHeartbeat()"
- "Accessory %{public}s was deleted, posting notification"
- "Client no longer active, stopping finding"
- "Failed to save disappear event %{public}@"
- "Failed to store '.connect' device event: %{public}@"
- "Failed to store '.disconnect' device event: %{public}@"
- "Saving .disappeared event"
- "serialNumberBasedPairingStatus(forPencilMACAddress:)"
```
