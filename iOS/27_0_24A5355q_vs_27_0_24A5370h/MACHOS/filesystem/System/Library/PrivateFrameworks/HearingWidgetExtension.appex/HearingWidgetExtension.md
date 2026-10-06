## HearingWidgetExtension

> `/System/Library/PrivateFrameworks/HearingWidgetExtension.appex/HearingWidgetExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0xa50` | `0xb4e` | **`+0xfe`** |
| `__DATA.__objc_const` | `0x878` | `0x908` | **`+0x90`** |
| `__TEXT.__objc_methlist` | `0x594` | `0x60c` | **`+0x78`** |
| `__DATA.__objc_selrefs` | `0x410` | `0x460` | **`+0x50`** |
| `__TEXT.__objc_methtype` | `0x25d` | `0x2a7` | **`+0x4a`** |
| `__TEXT.__auth_stubs` | `0x11a0` | `0x1180` | **`-0x20`** |
| `__DATA_CONST.__auth_got` | `0x8d8` | `0x8c8` | **`-0x10`** |
| `__TEXT.__text` | `0x15004` | `0x15014` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-527.0.0.0.0
+530.0.0.0.0

-  Symbols:   158
-  CStrings:  246
+  Symbols:   156
+  CStrings:  260
Symbols:
- _objc_release_x22
- _objc_retain_x23
Functions:
~ sub_1000020d8 : 2204 -> 2196
~ sub_1000074e0 -> sub_1000074d8 : 2176 -> 2172
~ sub_10000a8ec -> sub_10000a8e0 : 3396 -> 3356
~ sub_10000b630 -> sub_10000b5fc : 268 -> 280
~ sub_10000be54 -> sub_10000be2c : 280 -> 276
~ sub_10000def8 -> sub_10000decc : 836 -> 832
~ sub_10000edc8 -> sub_10000ed98 : 672 -> 668
~ sub_1000108a4 -> sub_100010870 : 2060 -> 2072
~ sub_100011bdc -> sub_100011bb4 : 2648 -> 2704
CStrings:
+ "@\"NSDictionary\"16@0:8"
+ "T@\"NSDictionary\",&,N"
+ "isMFiDeviceProtocol"
+ "leftMicrophoneInputGain"
+ "leftVolumeInputGain"
+ "rightMicrophoneInputGain"
+ "rightVolumeInputGain"
+ "setLeftMicrophoneInputGain:"
+ "setLeftVolumeInputGain:"
+ "setRightMicrophoneInputGain:"
+ "setRightVolumeInputGain:"
+ "shortDescription"
+ "v24@0:8@\"NSDictionary\"16"
+ "v24@0:8@16"
```
