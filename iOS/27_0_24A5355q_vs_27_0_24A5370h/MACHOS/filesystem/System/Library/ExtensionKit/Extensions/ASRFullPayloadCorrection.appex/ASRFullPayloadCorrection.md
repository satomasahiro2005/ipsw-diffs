## ASRFullPayloadCorrection

> `/System/Library/ExtensionKit/Extensions/ASRFullPayloadCorrection.appex/ASRFullPayloadCorrection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x228` | `0x230` | **`+0x8`** |
| `__TEXT.__text` | `0x3038` | `0x3030` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3600.64.114.1.5
+3600.70.8.0.0

+  - /usr/lib/swift/libswiftCoreAudio_Private.dylib

-  Symbols:   75
+  Symbols:   76
Symbols:
+ __swift_FORCE_LOAD_$_swiftCoreAudio_Private
Functions:
~ sub_1000031e0 -> sub_100003230 : 72 -> 68
~ sub_1000033ec -> sub_100003438 : 280 -> 276
```
