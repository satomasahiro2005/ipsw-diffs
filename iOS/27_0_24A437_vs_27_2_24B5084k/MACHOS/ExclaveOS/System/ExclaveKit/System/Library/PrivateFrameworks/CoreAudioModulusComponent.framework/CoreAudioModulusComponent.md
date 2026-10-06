## CoreAudioModulusComponent

> `/System/ExclaveKit/System/Library/PrivateFrameworks/CoreAudioModulusComponent.framework/CoreAudioModulusComponent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5e8c` | `0x5dc8` | **`-0xc4`** |
| `__TEXT.__cstring` | `0x1280` | `0x122f` | **`-0x51`** |
| `__TEXT.__oslogstring` | `0x35a` | `0x311` | **`-0x49`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-95.0.0.0.0
+95.202.0.0.0

-  CStrings:  81
+  CStrings:  79
Functions:
~ __ZN23CoreAudioModulusExclave18getDeviceTimestampEj : 844 -> 648
CStrings:
- "[%s] CoreAudioModulus: Using device %zu (identifier=%u) for useCaseID=%u"
- "[DEBUG][%s] CoreAudioModulus: Using device %zu (identifier=%u) for useCaseID=%u\n"
```
