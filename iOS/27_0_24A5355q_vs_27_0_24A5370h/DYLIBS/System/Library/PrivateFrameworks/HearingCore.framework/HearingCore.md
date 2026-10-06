## HearingCore

> `/System/Library/PrivateFrameworks/HearingCore.framework/HearingCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x76c0` | `0x7f90` | **`+0x8d0`** |
| `__TEXT.__oslogstring` | `0x3af` | `0x707` | **`+0x358`** |
| `__AUTH_CONST.__cfstring` | `0xd40` | `0xda0` | **`+0x60`** |
| `__TEXT.__cstring` | `0xb12` | `0xb5b` | **`+0x49`** |
| `__TEXT.__gcc_except_tab` | `0xe4` | `0x108` | **`+0x24`** |
| `__AUTH_CONST.__const` | `0x4a0` | `0x480` | **`-0x20`** |
| `__TEXT.__const` | `0xb4` | `0xd4` | **`+0x20`** |
| `__DATA.__bss` | `0x139` | `0x149` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x318` | `0x308` | **`-0x10`** |
| `__DATA_CONST.__const` | `0x390` | `0x398` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x830` | `0x838` | **`+0x8`** |

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

-  Symbols:   638
-  CStrings:  154
+  Symbols:   641
+  CStrings:  168
Symbols:
+ _CFPreferencesGetAppBooleanValue
+ ___block_descriptor_33_e24_v32?0"NSArray"8Q16^B24l
+ __os_feature_enabled_impl
+ _isBTLEAudioEnabled._isBTLEAudioEnabled
+ _isLEAudioEnabled._IsLEAudioEnabled
+ _kAXSPairedHearingUUIDsPreference
- ___39-[HCSettings _handlePreferenceChanged:]_block_invoke_2
- ___40-[HCSettings setValue:forPreferenceKey:]_block_invoke_2
- ___block_descriptor_32_e24_v32?0"NSArray"8Q16^B24l
CStrings:
+ "BT LEA 3 Enabled: yes"
+ "LEA 3 feature is enabled: yes"
+ "LeAudio"
+ "PairedHearingUUIDsPreference"
+ "[PairedHA-trace] Darwin notification received: %@ observer=%p observer-class=%{public}@"
+ "[PairedHA-trace] _handlePreferenceChanged key=%@ self-class=%{public}@ self=%p registeredBlocks=%lu"
+ "[PairedHA-trace] _registerForNotification adding Darwin observer key=%@ notification=%@ self-class=%{public}@ self=%p"
+ "[PairedHA-trace] _registerForNotification already-registered key=%@ self-class=%{public}@ self=%p"
+ "[PairedHA-trace] invoked block idx=%lu listenerKey=%@"
+ "[PairedHA-trace] invoking block idx=%lu listenerKey=%@ blockPresent=%d"
+ "[PairedHA-trace] registerUpdateBlock listener=%{public}@ listenerPtr=%p selector=%{public}@ self-class=%{public}@ self=%p totalBlocksForKey=%lu"
+ "[PairedHA-trace] setValue posting Darwin notification key=%@ notification=%@ domain=%@ self-class=%{public}@ self=%p valueIsNil=%d"
+ "com.apple.bluetooth"
+ "enableHALEAudio"
```
