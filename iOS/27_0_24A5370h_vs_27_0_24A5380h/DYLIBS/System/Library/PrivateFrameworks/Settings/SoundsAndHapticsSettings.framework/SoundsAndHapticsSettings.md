## SoundsAndHapticsSettings

> `/System/Library/PrivateFrameworks/Settings/SoundsAndHapticsSettings.framework/SoundsAndHapticsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x23364` | `0x2392c` | **`+0x5c8`** |
| `__TEXT.__cstring` | `0x3243` | `0x3423` | **`+0x1e0`** |
| `__AUTH_CONST.__objc_const` | `0x28b0` | `0x2a00` | **`+0x150`** |
| `__TEXT.__objc_methlist` | `0x1b4c` | `0x1c24` | **`+0xd8`** |
| `__DATA.__bss` | `0x680` | `0x5f0` | **`-0x90`** |
| `__DATA_DIRTY.__bss` | `0x2c0` | `0x350` | **`+0x90`** |
| `__DATA_CONST.__objc_selrefs` | `0x1870` | `0x18f0` | **`+0x80`** |
| `__TEXT.__gcc_except_tab` | `0x9e8` | `0xa50` | **`+0x68`** |
| `__TEXT.__oslogstring` | `0x118e` | `0x11c1` | **`+0x33`** |
| `__AUTH_CONST.__const` | `0x4f0` | `0x510` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x168` | `0x184` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0x768` | `0x780` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x928` | `0x940` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xa08` | `0xa10` | **`+0x8`** |

### Other Changes

```diff

-1129.0.0.0.0
+2027.0.1.100.0

-  Functions: 803
-  Symbols:   1410
-  CStrings:  454
+  Functions: 823
+  Symbols:   1441
+  CStrings:  458
Symbols:
+ -[SHSAudioPlayback _handleMediaServicesWereResetNotification:]
+ -[SHSAudioPlayback _pendingRingtoneAlertType]
+ -[SHSAudioPlayback _pendingRingtoneIdentifier]
+ -[SHSAudioPlayback _pendingRingtoneLoop]
+ -[SHSAudioPlayback _pendingSystemSoundIdentifier]
+ -[SHSAudioPlayback _pendingSystemSoundLoop]
+ -[SHSAudioPlayback _pendingSystemSoundVolume]
+ -[SHSAudioPlayback _retryingAfterReset]
+ -[SHSAudioPlayback _setup]
+ -[SHSAudioPlayback _tearDown]
+ -[SHSAudioPlayback deactivateAudioSession]
+ -[SHSAudioPlayback set_pendingRingtoneAlertType:]
+ -[SHSAudioPlayback set_pendingRingtoneIdentifier:]
+ -[SHSAudioPlayback set_pendingRingtoneLoop:]
+ -[SHSAudioPlayback set_pendingSystemSoundIdentifier:]
+ -[SHSAudioPlayback set_pendingSystemSoundLoop:]
+ -[SHSAudioPlayback set_pendingSystemSoundVolume:]
+ -[SHSAudioPlayback set_retryingAfterReset:]
+ GCC_except_table16
+ _AVAudioSessionMediaServicesWereResetNotification
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingRingtoneAlertType
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingRingtoneIdentifier
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingRingtoneLoop
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingSystemSoundIdentifier
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingSystemSoundLoop
+ _OBJC_IVAR_$_SHSAudioPlayback.__pendingSystemSoundVolume
+ _OBJC_IVAR_$_SHSAudioPlayback.__retryingAfterReset
+ ___42-[SHSAudioPlayback deactivateAudioSession]_block_invoke
+ ___62-[SHSAudioPlayback _handleMediaServicesWereResetNotification:]_block_invoke
+ ___block_descriptor_32_e20_v20?0B8"NSError"12l
+ _objc_setProperty_nonatomic_copy
CStrings:
+ "%s: Retrying ringtone preview '%{public}@' alertType '%{public}@'."
+ "%s: Retrying system sound preview '%{public}@'."
+ "-[SHSAudioPlayback _handleMediaServicesWereResetNotification:]_block_invoke"
+ "-[SHSAudioPlayback deactivateAudioSession]_block_invoke"
+ "Section footer on the Haptics options page; describes when haptics will play (or not play) for alarms, timers, alerts, and ringtones based on the selected option (Always Play, Play in Silent Mode, Don't Play in Silent Mode, Never Play)."
+ "Section header on the Haptics options page; introduces the four playback options that govern when haptics play for alarms, timers, alerts, and ringtones."
+ "v20@?0B8@\"NSError\"12"
- "%s: Failed to deactivate audio session with error '%{public}@'."
- "Section footer text explaining the effect of the selected options"
- "Section header"
```
