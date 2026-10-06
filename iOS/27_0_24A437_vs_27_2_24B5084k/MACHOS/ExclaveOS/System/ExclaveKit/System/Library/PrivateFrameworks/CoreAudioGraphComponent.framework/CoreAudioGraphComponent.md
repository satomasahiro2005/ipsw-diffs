## CoreAudioGraphComponent

> `/System/ExclaveKit/System/Library/PrivateFrameworks/CoreAudioGraphComponent.framework/CoreAudioGraphComponent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb220` | `0xaf24` | **`-0x2fc`** |
| `__TEXT.__cstring` | `0x1b24` | `0x1a2d` | **`-0xf7`** |
| `__TEXT.__oslogstring` | `0x689` | `0x5b2` | **`-0xd7`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-95.0.0.0.0
+95.202.0.0.0

-  CStrings:  125
+  CStrings:  117
Symbols:
+ ____Z14create_handlerv_block_invoke_4
- ___Z14create_handlerv_block_invoke
Functions:
~ ____Z14create_handlerv_block_invoke_3 : 296 -> 80
~ __ZN21CoreAudioGraphExclave14readFromDeviceEjyyjj : 876 -> 664
~ __ZN21CoreAudioGraphExclave13writeToDeviceEjyyjj : 836 -> 644
~ ____ZN21CoreAudioGraphExclave13writeToDeviceEjyyjj_block_invoke : 408 -> 264
CStrings:
- "[%s]   Device %u: writeToStream succeeded"
- "[%s] CoreAudioGraph: Reading from device %u (identifier=%u)"
- "[%s] CoreAudioGraph: Writing to device %u"
- "[%s] CoreAudioGraph: doIO() useCaseID=%u sampleTime=%llu hostTime=%llu"
- "[DEBUG][%s]   Device %u: writeToStream succeeded\n"
- "[DEBUG][%s] CoreAudioGraph: Reading from device %u (identifier=%u)\n"
- "[DEBUG][%s] CoreAudioGraph: Writing to device %u\n"
- "[DEBUG][%s] CoreAudioGraph: doIO() useCaseID=%u sampleTime=%llu hostTime=%llu\n"
```
