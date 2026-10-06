## AXTapToSpeakTime

> `/System/Library/PrivateFrameworks/AXTapToSpeakTime.framework/AXTapToSpeakTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6be8` | `0x6c74` | **`+0x8c`** |
| `__AUTH_CONST.__objc_const` | `0x910` | `0x940` | **`+0x30`** |
| `__DATA_CONST.__objc_selrefs` | `0x810` | `0x820` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x87c` | `0x88c` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x270` | `0x278` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x5c` | `0x60` | **`+0x4`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 165
-  Symbols:   477
+  Functions: 167
+  Symbols:   481
Symbols:
+ -[AXTapticChimeAsset _initWithChimeSoundType:audioFilePath:hapticsFilePath:isHourly:]
+ -[AXTapticChimeAsset isHourlyChime]
+ -[AXTapticChimesScheduler _scheduleChimeAudioPlayerForAsset:atDate:]
+ GCC_except_table145
+ GCC_except_table74
+ GCC_except_table91
+ GCC_except_table95
+ _OBJC_IVAR_$_AXTapticChimeAsset._isHourlyChime
+ _objc_retain_x23
- -[AXTapticChimeAsset _initWithChimeSoundType:audioFilePath:hapticsFilePath:]
- GCC_except_table144
- GCC_except_table73
- GCC_except_table90
- GCC_except_table94
```
