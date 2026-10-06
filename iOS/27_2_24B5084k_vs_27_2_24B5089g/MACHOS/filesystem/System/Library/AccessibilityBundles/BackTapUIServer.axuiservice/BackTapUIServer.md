## BackTapUIServer

> `/System/Library/AccessibilityBundles/BackTapUIServer.axuiservice/BackTapUIServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa808` | `0xa644` | **`-0x1c4`** |
| `__TEXT.__objc_methname` | `0x1104` | `0x1124` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x9e0` | `0xa00` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0xc0` | `0xb4` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0x408` | `0x410` | **`+0x8`** |
| `__TEXT.__const` | `0x7c8` | `0x7d0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x504` | `0x50c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x690` | `0x698` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3245.7.1.0.0
+3245.8.2.0.0

-  CStrings:  248
+  CStrings:  249
Symbols:
+ _AXDeviceHasJindo
+ _AXPerformBlockOnMainThreadAfterDelay
- _objc_release_x26
- _objc_retain_x1
Functions:
~ sub_22f4 : 572 -> 432
~ sub_2530 -> sub_24a4 : 336 -> 68
~ sub_2680 -> sub_24e8 : 336 -> 260
~ sub_27d0 -> sub_25ec : 68 -> 300
~ sub_b4dc -> sub_b3e0 : 528 -> 400
~ sub_b6ec -> sub_b570 : 784 -> 712
CStrings:
+ "_showConfirmationBannerForActionNamed:"
```
