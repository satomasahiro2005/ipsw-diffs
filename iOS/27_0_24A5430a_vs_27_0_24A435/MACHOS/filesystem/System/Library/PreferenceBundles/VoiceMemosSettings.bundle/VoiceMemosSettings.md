## VoiceMemosSettings

> `/System/Library/PreferenceBundles/VoiceMemosSettings.bundle/VoiceMemosSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x89c0` | `0x8a8c` | **`+0xcc`** |
| `__TEXT.__cstring` | `0x5ac` | `0x5cc` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x8a0` | `0x8b0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x458` | `0x460` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x280` | `0x288` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`

### Other Changes

```diff

-  Functions: 203
+  Functions: 204

-  CStrings:  53
+  CStrings:  54
CStrings:
+ "AUDIO_INPUT_DESCRIPTION_STUDIO"
+ "Localizable-Studio"
- "AUDIO_INPUT_DESCRIPTION"
```
