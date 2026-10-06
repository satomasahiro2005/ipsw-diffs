## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/MobileAssetDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26456c` | `0x264558` | **`-0x14`** |
| `__TEXT.__cstring` | `0x3f6f6` | `0x3f6e6` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff
Functions:
~ -[MADAutoAssetScheduler _scheduleSelector:triggeringAtIntervalSecs:withRemainingSecs:forPushedJob:forSetJob:withSetPolicy:triggeringIfLearned:resettingRemaining:isReadOnlyForResumeFromPersisted:] : 3152 -> 3168
~ _ccaes_arm_decrypt_key : 160 -> 144
~ +[MADAutoAssetScheduler isAssetTypeAtAggressiveFrequency:] : 156 -> 136
CStrings:
+ "Loaded built-in MobileAssetDaemon_Framework Aug  8 2026 19:07:18"
+ "Rave"
- "Loaded built-in MobileAssetDaemon_Framework Aug 10 2026 05:48:29"
- "RaveSeed"
```
