## LinkSource

> `/System/Library/PrivateFrameworks/CoreTime.framework/TimeSources/LinkSource.bundle/LinkSource`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x1e8` | `0x248` | **`+0x60`** |
| `__TEXT.__cstring` | `0xa9e` | `0xa76` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0x8cc` | `0x8f0` | **`+0x24`** |
| `__DATA.__objc_const` | `0x10b8` | `0x10d0` | **`+0x18`** |
| `__TEXT.__objc_methtype` | `0xd7b` | `0xd8e` | **`+0x13`** |
| `__DATA_CONST.__objc_protolist` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x258` | `0x260` | **`+0x8`** |
| `__TEXT.__objc_classname` | `0x8b` | `0x87` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-71.0.0.0.0
+72.0.0.0.0

-  CStrings:  585
+  CStrings:  586
Functions:
~ sub_3ec8 : 12 -> 92
~ sub_3ed4 -> sub_3f24 : 12 -> 40
~ sub_3eec -> sub_3f58 : 8 -> 12
~ sub_3f00 -> sub_3f70 : 12 -> 8
~ sub_3f18 -> sub_3f84 : 8 -> 12
~ sub_3f20 -> sub_3f90 : 8 -> 12
~ sub_3f50 -> sub_3fc4 : 124 -> 8
~ sub_3fcc : 92 -> 8
~ sub_4028 -> sub_3fd4 : 40 -> 124
CStrings:
+ "-[TMLSLinkSource rtcWhenBeyondUncertainty:]"
+ "-[TMLSLinkSource timeAtRtc:]"
+ "@\"TMTime\"24@0:8d16"
+ "TMTimeProvider"
- "-[TMLSLinkSource(_TimeProviderHacks) rtcWhenBeyondUncertainty:]"
- "-[TMLSLinkSource(_TimeProviderHacks) timeAtRtc:]"
- "_TimeProviderHacks"
```
