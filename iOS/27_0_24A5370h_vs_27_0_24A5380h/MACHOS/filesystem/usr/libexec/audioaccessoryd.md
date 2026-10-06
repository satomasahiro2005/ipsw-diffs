## audioaccessoryd

> `/usr/libexec/audioaccessoryd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25481c` | `0x257afc` | **`+0x32e0`** |
| `__TEXT.__cstring` | `0x58773` | `0x58a93` | **`+0x320`** |
| `__TEXT.__oslogstring` | `0x9aca` | `0x9d5a` | **`+0x290`** |
| `__DATA.__objc_data` | `0x33f0` | `0x3668` | **`+0x278`** |
| `__DATA.__data` | `0x5b10` | `0x5940` | **`-0x1d0`** |
| `__TEXT.__objc_methname` | `0x2d205` | `0x2d345` | **`+0x140`** |
| `__DATA_CONST.__const` | `0xcbf8` | `0xcce0` | **`+0xe8`** |
| `__DATA_CONST.__got` | `0x1048` | `0x1120` | **`+0xd8`** |
| `__TEXT.__eh_frame` | `0x2cb0` | `0x2d80` | **`+0xd0`** |
| `__DATA_CONST.__cfstring` | `0xb940` | `0xb9e0` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0xe844` | `0xe8ac` | **`+0x68`** |
| `__TEXT.__unwind_info` | `0x71d8` | `0x7240` | **`+0x68`** |
| `__DATA.__objc_const` | `0x1fe88` | `0x1fee8` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x1f1c0` | `0x1f220` | **`+0x60`** |
| `__TEXT.__swift5_capture` | `0x1f5c` | `0x1f94` | **`+0x38`** |
| `__TEXT.__const` | `0x4d30` | `0x4d00` | **`-0x30`** |
| `__DATA.__objc_selrefs` | `0x92b8` | `0x92e0` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x20e4` | `0x210c` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x1b9b` | `0x1bbb` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1ec4` | `0x1ee4` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x41f9` | `0x4209` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x198c` | `0x1998` | **`+0xc`** |
| `__DATA.__objc_ivar` | `0x187c` | `0x1884` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
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
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-40.31.1.0.0
+40.33.1.0.0

-  Functions: 11995
+  Functions: 12022

-  CStrings:  16305
+  CStrings:  16342
CStrings:
+ "### Missing BT address in head tracking state message"
+ "-[BTAudioDriverController _headTrackingStateChangedMessageReceived:]"
+ "-[SR3PRoutingDaemon _headTrackingStateChanged:btAddress:]"
+ "Activate message missing deviceConfiguration, cannot register connection"
+ "Head Gesture Manager (enable when there is media): headGestureToggle=%s, deviceInANCMode=%s, mediaIsPlaying=%s, shouldStart=%s"
+ "HeadTrackingStateChanged: Could not resolve UUID for %@, skipping notification"
+ "HeadTrackingStateChanged: No BT address provided"
+ "HeadTrackingStateChanged: Spatial head tracking %s for %@"
+ "New write client connected, pending device UUID registration"
+ "No registered write connection for UUID %s, head tracking state not sent"
+ "Notification: spatial head tracking changed to %{bool}d for UUID %s"
+ "Received head tracking notification with missing userInfo"
+ "Registered write connection for device UUID: %s on activate (total: %ld)"
+ "SR3PHeadTracking"
+ "SRSpatialHeadTrackingBTAddressKey"
+ "SRSpatialHeadTrackingDeviceUUIDKey"
+ "SRSpatialHeadTrackingEnabledKey"
+ "SRSpatialHeadTrackingStateChangedNotification"
+ "Sent head tracking state %{bool}d to write client for UUID %s"
+ "Spatial head tracking state changed: %s for %@"
+ "TB,R,V_spatialHeadTrackingEnabled"
+ "Using forced value for head tracking support %u"
+ "Write client disconnected for UUID(s) %s (remaining: %ld)"
+ "Write connection for UUID %s already registered, skipping"
+ "XPC listener not activated"
+ "XPC listeners deactivated"
+ "_headTrackingStateChanged:btAddress:"
+ "_headTrackingStateChangedMessageReceived:"
+ "_spatialHeadTrackingEnabled"
+ "_spatialHeadTrackingEnabledPerDevice"
+ "_writeDataListenerConnections"
+ "disabled"
+ "enabled"
+ "handleHeadTrackingStateChanged:"
+ "headTrackingState"
+ "headTrackingStateChanged:btAddress:"
+ "kAccAudioMsgArgHeadTrackingEnabled"
+ "kBTAudioMsgProperty3pHeadTrackingSupport"
+ "spatialHeadTrackingEnabled"
- "Head Gesture Manager: headGestureToggle=%s, deviceInANCMode=%s, mediaIsPlaying=%s, shouldStart=%s"
- "New write client connected to AudioAccessorySensor XPC service"
```
