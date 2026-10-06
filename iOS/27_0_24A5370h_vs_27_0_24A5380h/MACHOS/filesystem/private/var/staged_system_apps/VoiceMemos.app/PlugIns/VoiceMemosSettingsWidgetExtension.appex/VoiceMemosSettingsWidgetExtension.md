## VoiceMemosSettingsWidgetExtension

> `/private/var/staged_system_apps/VoiceMemos.app/PlugIns/VoiceMemosSettingsWidgetExtension.appex/VoiceMemosSettingsWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d19c` | `0x1cf2c` | **`-0x270`** |
| `__TEXT.__cstring` | `0x15c4` | `0x14f4` | **`-0xd0`** |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x200` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1c8` | `0x1a8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xdb8` | `0xdc0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-1431.0.0.0.0
+1433.0.0.0.0

-  Functions: 1131
+  Functions: 1132

-  CStrings:  196
+  CStrings:  191
CStrings:
+ "RCAppAnalyticsUserIDResetKey"
- "/RCAppAnalyticsUserIDResetKey"
- "/RCVoiceMemosAudioQualityKey"
- "/RCVoiceMemosChannelConfigurationKey"
- "/RCVoiceMemosRecentlyDeletedWindowKey"
- "/RCVoiceMemosStereoRecordingKey"
- "/RCVoiceMemosUseLocationBasedNaming"
```
