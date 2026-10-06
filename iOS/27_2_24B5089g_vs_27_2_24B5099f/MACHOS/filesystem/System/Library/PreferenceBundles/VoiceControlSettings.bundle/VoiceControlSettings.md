## VoiceControlSettings

> `/System/Library/PreferenceBundles/VoiceControlSettings.bundle/VoiceControlSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x3860` | `0x3820` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x3fb6` | `0x3f7c` | **`-0x3a`** |
| `__TEXT.__cstring` | `0x1805` | `0x1835` | **`+0x30`** |
| `__DATA.__objc_const` | `0x17d0` | `0x17f0` | **`+0x20`** |
| `__DATA_CONST.__cfstring` | `0x16c0` | `0x16e0` | **`+0x20`** |
| `__TEXT.__text` | `0x1697c` | `0x16990` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0x1368` | `0x1358` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x78` | `0x7c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-191.2.1.0.0
+191.2.3.0.0
Symbols:
+ _CACVCIGetSettingsPresentation
- _AXDeviceSupportsAppleIntelligence
Functions:
~ sub_cae0 : 5664 -> 5668
~ sub_f578 -> sub_f57c : 168 -> 184
CStrings:
+ "FLEXIBLE_ITEM_NAMES_DISABLED_FOOTER"
+ "_vciPresentationSnapshot"
- "activeLocaleSupportsVoiceControlIntelligence"
- "voiceControlIntelligenceSwitchEnabled"
```
