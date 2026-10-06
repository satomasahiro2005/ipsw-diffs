## BTAudioHALPlugin

> `/System/Library/Audio/Plug-Ins/HAL/BTAudioHALPlugin.driver/BTAudioHALPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x16233` | `0x16af8` | **`+0x8c5`** |
| `__TEXT.__text` | `0x7ccd4` | `0x7d47c` | **`+0x7a8`** |
| `__DATA_CONST.__const` | `0x5318` | `0x5338` | **`+0x20`** |
| `__TEXT.__const` | `0x1aac` | `0x1a9c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1cd8` | `0x1cd0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-2700.41.1.1.0
+2700.43.0.0.0

-  Functions: 2861
+  Functions: 2872

-  CStrings:  2976
+  CStrings:  2994
CStrings:
+ "BTAudioAVNotificationMonitor: choosePickableRoute — _systemController is nil, cannot query pickable route"
+ "BTAudioAVNotificationMonitor: choosePickableRoute — route is not BT headphones/headset (route=%@), clearing _currentDeviceUID %@"
+ "BTAudioAVNotificationMonitor: choosePickableRoute — skipping, monitor is shutting down"
+ "BTAudioAVNotificationMonitor: processManualVolumeUpdates — skipping enabled=%d, monitor is shutting down"
+ "BTAudioAVNotificationMonitor: registerPersonalizedVolumeListener block — skipping device %u (%@), monitor shut down before block executed"
+ "BTAudioAVNotificationMonitor: registerPersonalizedVolumeListener mirror block — skipping address mirror for %@, monitor shut down"
+ "BTAudioAVNotificationMonitor: registerPersonalizedVolumeListener — skipping device %u (%@), monitor is shutting down"
+ "BTAudioAVNotificationMonitor: removeAllNotificationListeners — skipping, _systemController is nil (subscription may have failed at init)"
+ "BTAudioAVNotificationMonitor: sendManualVolumeUpdate — skipping volume=%u uid=%@, monitor is shutting down"
+ "BTAudioAVNotificationMonitor: unRegisterPersonalizedVolumeListener block — skipping device %u (%@), monitor shut down before block executed"
+ "BTAudioAVNotificationMonitor: unRegisterPersonalizedVolumeListener mirror block — skipping address removal for %@, monitor shut down"
+ "BTAudioAVNotificationMonitor: unRegisterPersonalizedVolumeListener — skipping device %u (%@), monitor is shutting down"
+ "BTAudioAVNotificationMonitor: updateVolumeDelta — _systemController is nil, cannot forward delta=%f to MXSystemController"
+ "BTAudioAVNotificationMonitor: updateVolumeDelta — skipping delta=%f, monitor is shutting down"
+ "BTAudioAVNotificationMonitor: updateVolumeForCategories — _systemController is nil, cannot forward media=%f tel=%f voice=%f to MXSystemController"
+ "BTAudioAVNotificationMonitor: updateVolumeForCategories — skipping media=%f tel=%f voice=%f, monitor is shutting down"
+ "HostGrid Anchor c:%llu,len:%u,Q:%f~%u,curr:%f,bufSize:%u,Seq:%x"
+ "HostGrid jumped back c:%llu,Q:%f~%u,curr:%f,ATs:%f,bufSize:%u"
+ "HostGrid reA drop:%f >= bufSize:%u, forcing re-anchor; prevATs:%f,prevQ:%f~%u,curr:%f,ATs:%f"
+ "HostGrid reA prevATs:%f,prevQ:%f~%u,drop:%f,Q:%f~%u,curr:%f,ATs:%f,bufSize:%u,Seq:%u , @ %llu"
+ "HostGrid should not come here c:%llu,Q:%f~%u,curr:%f,ATs:%f,bufSize:%u"
+ "InvalidateAllUnifiedAudioDevices: skipping BTAudioAVNotificationMonitor shutdown — transient XPC disconnect, monitor remains active for reconnect"
- "HostGrid Anchor c:%llu,len:%u,Q:%f~%u,curr:%f,Seq:%x"
- "HostGrid jumped back c:%llu,Q:%f~%u,curr:%f,ATs:%f"
- "HostGrid reA prevATs:%f,prevQ:%f~%u,drop:%f,Q:%f~%u,curr:%f,ATs:%f,Seq:%u , @ %llu"
- "HostGrid should not come here c:%llu,Q:%f~%u,curr:%f,ATs:%f"
```
