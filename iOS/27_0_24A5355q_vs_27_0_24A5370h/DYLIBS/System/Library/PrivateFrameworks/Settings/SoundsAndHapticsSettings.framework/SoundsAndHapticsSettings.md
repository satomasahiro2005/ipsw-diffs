## SoundsAndHapticsSettings

> `/System/Library/PrivateFrameworks/Settings/SoundsAndHapticsSettings.framework/SoundsAndHapticsSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22eb0` | `0x23364` | **`+0x4b4`** |
| `__TEXT.__oslogstring` | `0x1103` | `0x118e` | **`+0x8b`** |
| `__TEXT.__cstring` | `0x31d3` | `0x3243` | **`+0x70`** |
| `__AUTH_CONST.__objc_const` | `0x2850` | `0x28b0` | **`+0x60`** |
| `__TEXT.__objc_methlist` | `0x1b04` | `0x1b4c` | **`+0x48`** |
| `__AUTH_CONST.__cfstring` | `0x1b00` | `0x1b40` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1838` | `0x1870` | **`+0x38`** |
| `__DATA.__objc_ivar` | `0x160` | `0x168` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x920` | `0x928` | **`+0x8`** |

### Other Changes

```diff

-1127.0.0.0.0
+1129.0.0.0.0

-  Functions: 794
-  Symbols:   1401
-  CStrings:  448
+  Functions: 803
+  Symbols:   1410
+  CStrings:  454
Symbols:
+ -[SHSSoundsPrefController _alarmVolumeSliderSpecifier]
+ -[SHSSoundsPrefController _alertVolumeSliderSpecifier]
+ -[SHSSoundsPrefController _queryRingtoneMinimumVolume]
+ -[SHSSoundsPrefController _updateRingtoneSliderMinimum]
+ -[SHSSoundsPrefController set_alarmVolumeSliderSpecifier:]
+ -[SHSSoundsPrefController set_alertVolumeSliderSpecifier:]
+ _OBJC_IVAR_$_SHSSoundsPrefController.__alarmVolumeSliderSpecifier
+ _OBJC_IVAR_$_SHSSoundsPrefController.__alertVolumeSliderSpecifier
+ ___55-[SHSSoundsPrefController _updateRingtoneSliderMinimum]_block_invoke
CStrings:
+ "%s: Failed to query ringtone minimum volume: %{public}@."
+ "%s: Ringtone minimum volume: %f."
+ "%s: getMinimumVolume returned invalid value: %f."
+ "-[SHSSoundsPrefController _queryRingtoneMinimumVolume]"
+ "MATCH_ALARM_RINGTONE_VOLUME"
+ "MATCH_RINGTONE_VOLUME"
+ "\xf0\""
- "\xf2"
```
