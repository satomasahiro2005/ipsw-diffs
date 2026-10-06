## AudioSessionServer

> `/System/Library/PrivateFrameworks/AudioSessionServer.framework/AudioSessionServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6ef6c` | `0x6f430` | **`+0x4c4`** |
| `__TEXT.__oslogstring` | `0x52a3` | `0x547e` | **`+0x1db`** |
| `__TEXT.__gcc_except_tab` | `0xa600` | `0xa638` | **`+0x38`** |
| `__TEXT.__const` | `0xbf0` | `0xbd0` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x2d30` | `0x2d48` | **`+0x18`** |
| `__TEXT.__cstring` | `0x48ff` | `0x490c` | **`+0xd`** |

### Other Changes

```diff

-449.105.0.0.0
+449.107.0.0.0

-  Symbols:   2595
-  CStrings:  1005
+  Symbols:   2596
+  CStrings:  1014
Symbols:
+ __ZN12_GLOBAL__N_131queryHardwareOnlyLatencySamplesEjjPKc
+ __ZN4avas6server18DeviceTimeObserver17setFixedLatenciesEjNSt3__18optionalIjEES4_
+ __ZN4avas6server18DeviceTimeObserver28sessionsObservingDeviceEventEj24AVAudioIOControllerEventbNSt3__18optionalIjEES5_
- __ZN4avas6server18DeviceTimeObserver15setFixedLatencyEjyy
- __ZN4avas6server18DeviceTimeObserver28sessionsObservingDeviceEventEj24AVAudioIOControllerEventb
CStrings:
+ "%25s:%-5d Warning - ignoring btPts that has bad host time: %llu (expected > previousMts i.e.: %llu) (device ID: %u)"
+ "%25s:%-5d Warning - ignoring btPts with negative sample time: %.3f (pts: %.3f)(device ID: %u)"
+ "%25s:%-5d dto device ID: %u has bad sample rate: %f"
+ "%25s:%-5d dto failed to get %s device constant latency (device ID: %u)"
+ "%25s:%-5d dto latency not supported on %s scope (device ID: %u)"
+ "%25s:%-5d dto set fixed input latency: %.2f ms for device ID: %u"
+ "%25s:%-5d dto set fixed output latency: %.2f ms for device ID: %u"
+ "%25s:%-5d dto start event for device ID: %u, supportsDynamicLatency: %d"
+ "%25s:%-5d dto starting BT presentation time poller for device ID: %u)"
+ "%25s:%-5d dto stop event for device ID: %u)"
+ "%25s:%-5d dto stopping BT presentation time poller for device ID: %u)"
+ "%25s:%-5d dto update sample rate: %f for device ID: %u"
+ "input"
+ "output"
- "%25s:%-5d Warning - ignoring btPts has zero/bad PTS! %.5f (sampleTime: %.5f)"
- "%25s:%-5d Warning - ignoring btPts that has bad host time: %llu (expected > previousMts i.e.: %llu)"
- "%25s:%-5d failed to get output device constant latency"
- "%25s:%-5d starting BT presentation time poller for device ID: %u)"
- "%25s:%-5d stopping BT presentation time poller for device ID: %u)"
```
