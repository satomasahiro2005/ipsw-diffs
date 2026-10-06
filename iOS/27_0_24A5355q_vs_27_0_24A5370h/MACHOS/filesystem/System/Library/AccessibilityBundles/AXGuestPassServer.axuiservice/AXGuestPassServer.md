## AXGuestPassServer

> `/System/Library/AccessibilityBundles/AXGuestPassServer.axuiservice/AXGuestPassServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x26ba8` | `0x26cc4` | **`+0x11c`** |
| `__TEXT.__oslogstring` | `0x120a` | `0x127a` | **`+0x70`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3229.1.6.0.0
+3232.3.0.0.0

-  CStrings:  310
+  CStrings:  311
Functions:
~ sub_3708 : 6324 -> 6312
~ sub_a230 -> sub_a224 : 280 -> 276
~ sub_e0a0 -> sub_e090 : 3612 -> 3620
~ sub_13e90 -> sub_13e88 : 252 -> 276
~ sub_13f8c -> sub_13f9c : 256 -> 264
~ sub_1ac50 -> sub_1ac68 : 164 -> 180
~ sub_1bca4 -> sub_1bccc : 1144 -> 1364
~ sub_1d334 -> sub_1d438 : 528 -> 532
~ sub_1f37c -> sub_1f484 : 368 -> 360
~ sub_24c5c -> sub_24d5c : 2580 -> 2604
~ sub_28254 -> sub_2836c : 328 -> 332
CStrings:
+ "AXGuestPassNetworkConnection: Listener already attached to underlying transport, skipping setup."
```
