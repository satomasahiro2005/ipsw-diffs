## ASRFullPayloadCorrection

> `/System/Library/ExtensionKit/Extensions/ASRFullPayloadCorrection.appex/ASRFullPayloadCorrection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3030` | `0x2fac` | **`-0x84`** |
| `__TEXT.__const` | `0x30e` | `0x35e` | **`+0x50`** |
| `__DATA_CONST.__got` | `0x50` | `0x58` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.70.47.11.1
+3605.10.1.0.0

-  Symbols:   76
+  Symbols:   78
Symbols:
+ _ASRFullPayloadCorrectionVersionNumber
+ _ASRFullPayloadCorrectionVersionString
Functions:
~ sub_100001f8c : 1392 -> 1260
```
