## BluetoothSettings

> `/System/Library/PreferenceBundles/BluetoothSettings.bundle/BluetoothSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22b98` | `0x22e38` | **`+0x2a0`** |
| `__AUTH_CONST.__cfstring` | `0x2220` | `0x22c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x1a31` | `0x1a91` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x2132` | `0x2172` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1944` | `0x196c` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2b0` | `0x2d0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1708` | `0x1728` | **`+0x20`** |
| `__DATA.__bss` | `0x140` | `0x150` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x5f8` | `0x608` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x750` | `0x760` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x6d8` | `0x6e0` | **`+0x8`** |

### Other Changes

```diff

-2700.13.0.0.0
+2700.14.0.0.0

-  Functions: 594
-  Symbols:   1161
-  CStrings:  503
+  Functions: 600
+  Symbols:   1172
+  CStrings:  512
Symbols:
+ -[BTSDevice isLEAudioSupported]
+ -[BTSDeviceLE isLEAudioSupported]
+ -[BTSDevicesController isLEAudioLiveOnEnabled]
+ -[BTSDevicesController markLEAudioDevice:]
+ GCC_except_table205
+ _CBUUIDCommonAudioServiceString
+ _CBUUIDTelephonyMediaAudioServiceString
+ _CFPreferencesCopyAppValue
+ ___46-[BTSDevicesController isLEAudioLiveOnEnabled]_block_invoke
+ _isLEAudioLiveOnEnabled.flagExists
+ _isLEAudioLiveOnEnabled.onceTokenLEAudio
+ _isLEAudioLiveOnEnabled.osFeatureLEAudioEnabled
- GCC_except_table202
CStrings:
+ "Accessibility"
+ "LE"
+ "LEAudio - liveOnEnabled: %d, featureEnabled: %d"
+ "LEAudioLiveOnEnable"
+ "LeAudio"
+ "Mark LEAudio device"
+ "[LEAudio]"
+ "_LEAUDIO_DEVICE_"
+ "com.apple.MobileBluetooth.debug"
```
