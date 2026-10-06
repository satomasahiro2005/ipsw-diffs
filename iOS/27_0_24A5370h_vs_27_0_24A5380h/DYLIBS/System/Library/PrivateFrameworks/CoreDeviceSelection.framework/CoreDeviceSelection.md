## CoreDeviceSelection

> `/System/Library/PrivateFrameworks/CoreDeviceSelection.framework/CoreDeviceSelection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe3e4c` | `0xe7ba4` | **`+0x3d58`** |
| `__TEXT.__eh_frame` | `0xb1d8` | `0xb6b0` | **`+0x4d8`** |
| `__AUTH_CONST.__const` | `0x9cc9` | `0x9f99` | **`+0x2d0`** |
| `__TEXT.__cstring` | `0x151f` | `0x164f` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x19e8` | `0x1b08` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x47a0` | `0x4898` | **`+0xf8`** |
| `__TEXT.__const` | `0xce80` | `0xcf38` | **`+0xb8`** |
| `__TEXT.__swift_as_cont` | `0x5c4` | `0x63c` | **`+0x78`** |
| `__TEXT.__swift_as_entry` | `0x400` | `0x434` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x450` | `0x484` | **`+0x34`** |
| `__TEXT.__oslogstring` | `0x3b3f` | `0x3b6f` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1c02` | `0x1be2` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x3c0e` | `0x3bf2` | **`-0x1c`** |
| `__DATA.__data` | `0x2e20` | `0x2e08` | **`-0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x2abc` | `0x2ab0` | **`-0xc`** |

### Other Changes

```diff

-3600.49.5.1.1
+3600.49.8.0.0

-  Functions: 6722
-  Symbols:   1842
-  CStrings:  426
+  Functions: 6841
+  Symbols:   1835
+  CStrings:  436
Symbols:
+ _symbolic _____y_____yx_GG 15Synchronization5MutexVAARi_zrlE 19CoreDeviceSelection19DefaultScoreServiceC5State33_872076D213C37384FDF77211EF8D8485LLV
- _get_type_metadata 15Synchronization5MutexVy19CoreDeviceSelection07DefaultD7ServiceC5State33_2150AF2A339D9E4B1F354046724BE9B3LLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy19CoreDeviceSelection11SignalStoreC5State33_BE8C0FD9A30473AE7C3BF68C510D668ELLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVy19CoreDeviceSelection13ScoreProducerC5State33_92B2C41CB0C221D59F6D02A2E04CB8BALLVG noncopyable
- _get_type_metadata 15Synchronization5MutexVySDy19CoreDeviceSelection19AnySendableHashableVAD0dE0O0D0_p_AD0D9ScoreDataVSgtGG noncopyable
- _get_type_metadata 15Synchronization5MutexVySbG noncopyable
- _get_type_metadata 15Synchronization6AtomicVySiG noncopyable
- _get_type_metadata 19CoreDeviceSelection0bC0O4RoleRzl15Synchronization5MutexVyAA19DefaultScoreServiceC5State33_872076D213C37384FDF77211EF8D8485LLVyx_GG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
CStrings:
+ "BluetoothTransportFactory.make"
+ "BluetoothTransportMode resolved to %s"
+ "buildConfigProcessorFactory"
+ "createMessagingManager"
+ "discoveryService.start"
+ "getConfig"
+ "messageCenter.start"
+ "registerSignalStoreProcessorServices"
+ "setupMessageCenter"
+ "signalStoreServiceProvider.service"
+ "snapshotInitialDeviceState"
+ "startDiscoveryService"
- "com.apple.siri.deviceselectiond"
- "host_process_daemon"
```
