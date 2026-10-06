## SilexVideo

> `/System/Library/PrivateFrameworks/SilexVideo.framework/SilexVideo`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10868` | `0x11148` | **`+0x8e0`** |
| `__AUTH_CONST.__objc_const` | `0x3cc0` | `0x3de8` | **`+0x128`** |
| `__TEXT.__objc_methlist` | `0x2098` | `0x2180` | **`+0xe8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1648` | `0x16e0` | **`+0x98`** |
| `__TEXT.__gcc_except_tab` | `0x42c` | `0x47c` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x4e0` | `0x508` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x650` | `0x678` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x440` | `0x460` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4b3` | `0x4d3` | **`+0x20`** |
| `__DATA.__objc_ivar` | `0x210` | `0x228` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x310` | `0x320` | **`+0x10`** |

### Other Changes

```diff

-5916.1.0.0.0
+5920.0.0.0.0

-  Functions: 581
-  Symbols:   1336
-  CStrings:  62
+  Functions: 603
+  Symbols:   1368
+  CStrings:  65
Symbols:
+ -[SVAVPlayer addAudioModeObserversIfNeeded]
+ -[SVAVPlayer intendedAudioMode]
+ -[SVAVPlayer isEffectivelySilent]
+ -[SVAVPlayer muteObserver]
+ -[SVAVPlayer setIntendedAudioMode:]
+ -[SVAVPlayer setMuteObserver:]
+ -[SVAVPlayer setVolumeObserver:]
+ -[SVAVPlayer updateEffectiveAudioMode]
+ -[SVAVPlayer volumeObserver]
+ -[SVPlaybackCoordinator dealloc]
+ -[SVPlaybackCoordinator lastReportedTime]
+ -[SVPlaybackCoordinator registerTimeJumpObserver]
+ -[SVPlaybackCoordinator setLastReportedTime:]
+ -[SVPlaybackCoordinator setTimeJumpNotificationObserver:]
+ -[SVPlaybackCoordinator timeJumpNotificationObserver]
+ -[SVVideoPlayerViewController advanceWithMuted:]
+ -[SVVideoPlayerViewController audioMode]
+ -[SVVideoPlayerViewController initWithAudioMode:]
+ -[SVVideoPlayerViewController setAudioMode:]
+ GCC_except_table12
+ GCC_except_table15
+ GCC_except_table19
+ GCC_except_table23
+ GCC_except_table25
+ GCC_except_table54
+ GCC_except_table61
+ _AVPlayerItemTimeJumpedNotification
+ _OBJC_CLASS_$_NSOperationQueue
+ _OBJC_IVAR_$_SVAVPlayer._intendedAudioMode
+ _OBJC_IVAR_$_SVAVPlayer._muteObserver
+ _OBJC_IVAR_$_SVAVPlayer._volumeObserver
+ _OBJC_IVAR_$_SVPlaybackCoordinator._lastReportedTime
+ _OBJC_IVAR_$_SVPlaybackCoordinator._timeJumpNotificationObserver
+ _OBJC_IVAR_$_SVVideoPlayerViewController._audioMode
+ ___43-[SVAVPlayer addAudioModeObserversIfNeeded]_block_invoke
+ ___43-[SVAVPlayer addAudioModeObserversIfNeeded]_block_invoke_2
+ ___49-[SVPlaybackCoordinator registerTimeJumpObserver]_block_invoke
+ ___49-[SVVideoPlayerViewController initWithAudioMode:]_block_invoke
+ ___block_descriptor_40_e8_32w_e24_v16?0"NSNotification"8lw32l8
- GCC_except_table10
- GCC_except_table13
- GCC_except_table20
- GCC_except_table22
- GCC_except_table39
- GCC_except_table59
- ___35-[SVVideoPlayerViewController init]_block_invoke
CStrings:
+ "\""
+ "#7"
+ "o"
+ "v16@?0@\"NSNotification\"8"
+ "volume"
- "#5"
- "_"
```
