## vot

> `/System/Library/CoreServices/VoiceOverTouch.app/vot`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17c5b4` | `0x17c830` | **`+0x27c`** |
| `__TEXT.__oslogstring` | `0x9f3f` | `0x9f85` | **`+0x46`** |
| `__TEXT.__objc_methname` | `0x384e8` | `0x38528` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3c90` | `0x3cb0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2a460` | `0x2a480` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1e58` | `0x1e68` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0xc8e8` | `0xc8f0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Symbols:   2326
-  CStrings:  12386
+  Symbols:   2328
+  CStrings:  12388
Symbols:
+ _AXDeviceSupports8TouchesInBSI
+ _AXDeviceSupportsBrailleSensingMode
+ __AXSBrailleSensingModeSetExpected
- _AXDeviceSupportsManyTouches
Functions:
~ sub_100047b44 : 5332 -> 5340
~ sub_10004f860 -> sub_10004f868 : 896 -> 904
~ sub_1000ced10 -> sub_1000ced20 : 5340 -> 5352
~ sub_100118368 -> sub_100118384 : 2116 -> 2124
~ sub_100119508 -> sub_10011952c : 588 -> 736
~ sub_10011999c -> sub_100119a54 : 220 -> 388
~ sub_10011bf34 -> sub_10011c094 : 88 -> 180
~ sub_10011f294 -> sub_10011f450 : 1220 -> 1256
~ sub_100136a44 -> sub_100136c24 : 1312 -> 1316
~ sub_100137de8 -> sub_100137fcc : 4000 -> 4036
~ sub_1001401b8 -> sub_1001403c0 : 2084 -> 2148
~ sub_10015743c -> sub_100157684 : 8344 -> 8348
~ sub_100177f3c -> sub_100178188 : 980 -> 992
~ sub_100179d58 -> sub_100179fb0 : 360 -> 364
~ sub_10017a018 -> sub_10017a274 : 356 -> 360
~ sub_10017c2b8 -> sub_10017c518 : 1692 -> 1720
CStrings:
+ "BSI-DIAG: setTypingMode:%ld, supports8=%d, singleHand=%d -> expect=%d"
+ "voiceOverTouchBrailleGesturesAlwaysUseEightDotsInCommandMode"
```
