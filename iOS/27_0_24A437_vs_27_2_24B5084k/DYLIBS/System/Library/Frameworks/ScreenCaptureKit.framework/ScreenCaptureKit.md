## ScreenCaptureKit

> `/System/Library/Frameworks/ScreenCaptureKit.framework/ScreenCaptureKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36fac` | `0x3706c` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x3c42` | `0x3c03` | **`-0x3f`** |
| `__AUTH_CONST.__objc_const` | `0x8b30` | `0x8b50` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xd20` | `0xd10` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6d0` | `0x6c8` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x5c8` | `0x5d0` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x2300` | `0x2308` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5a0` | `0x5a4` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-740.63.1.2.0
+765.9.1.0.0

-  Functions: 1456
-  Symbols:   2572
-  CStrings:  871
+  Functions: 1453
+  Symbols:   2573
+  CStrings:  870
Symbols:
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_IVAR_$_SCControlCenterManager._observerLock
- _notify_register_check
Functions:
~ -[SCContentFilter setContentsAndStreamTypeEmbedded] : 800 -> 956
~ -[RPThermalPressure startMonitoring] : 176 -> 160
~ -[SCControlCenterManager init] : 652 -> 656
~ ___43-[SCControlCenterManager registerObserver:]_block_invoke : 564 -> 592
~ ___45-[SCControlCenterManager unregisterObserver:]_block_invoke : 564 -> 592
~ -[SCControlCenterManager callObserver:] : 376 -> 404
~ ___59-[SCStream(SCContentSharing) startRemoteVideoReceiveQueue:]_block_invoke : 2008 -> 2064
~ ___59-[SCStream(SCContentSharing) startRemoteAudioReceiveQueue:]_block_invoke : 568 -> 636
~ ___64-[SCStream(SCContentSharing) startRemoteMicrophoneReceiveQueue:]_block_invoke : 552 -> 620
~ ___59-[SCStream(SCContentSharing) startRemoteVideoReceiveQueue:]_block_invoke.cold.8 : 76 -> 88
~ ___59-[SCStream(SCContentSharing) startRemoteVideoReceiveQueue:]_block_invoke.cold.9 : 88 -> 96
~ ___59-[SCStream(SCContentSharing) startRemoteVideoReceiveQueue:]_block_invoke.cold.10 : 96 -> 112
- ___59-[SCStream(SCContentSharing) startRemoteVideoReceiveQueue:]_block_invoke.cold.11
~ ___59-[SCStream(SCContentSharing) startRemoteAudioReceiveQueue:]_block_invoke.cold.2 : 76 -> 112
- ___59-[SCStream(SCContentSharing) startRemoteAudioReceiveQueue:]_block_invoke.cold.3
~ ___64-[SCStream(SCContentSharing) startRemoteMicrophoneReceiveQueue:]_block_invoke.cold.2 : 76 -> 112
- ___64-[SCStream(SCContentSharing) startRemoteMicrophoneReceiveQueue:]_block_invoke.cold.3
CStrings:
+ " [DEBUG] %{public}s:%d streamOutput NOT found. Dropping frame"
- " [ERROR] %{public}s:%d stream output NOT found. Dropping frame"
- " [ERROR] %{public}s:%d streamOutput NOT found. Dropping frame"
```
