## VoiceControlSettings

> `/System/Library/PreferenceBundles/VoiceControlSettings.bundle/VoiceControlSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16554` | `0x1697c` | **`+0x428`** |
| `__TEXT.__oslogstring` | `0x195` | `0x3a5` | **`+0x210`** |
| `__TEXT.__const` | `0x5f4` | `0x614` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc8` | `0xe0` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xd90` | `0xda0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x6d8` | `0x6e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-185.0.0.0.0
+188.0.0.0.0

-  Symbols:   375
-  CStrings:  1016
+  Symbols:   376
+  CStrings:  1021
Symbols:
+ _AXAIWhiteGloveLoggingEnabled
Functions:
~ sub_cae0 : 4600 -> 5664
CStrings:
+ "rdar://167076301 CACSettingsController disabling ATTENTION_AWARE_ACTION switch cellType=%ld cellClass=%{public}@"
+ "rdar://167076301 CACSettingsController final switch id=%{public}@ cellClass=%{public}@ enabled=%{public}@"
+ "rdar://167076301 CACSettingsController specifiers enter loadedCount=%lu isCACSetup=%d isAttentionAwarenessEnabled=%d"
+ "rdar://167076301 CACSettingsController specifiers exit totalCount=%lu switchCount=%lu"
+ "rdar://167076301 CACSettingsController switch specifier id=%{public}@ cellType=%ld cellClass=%{public}@"
```
