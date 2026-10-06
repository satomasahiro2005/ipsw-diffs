## CompanionSetup

> `/Applications/CompanionSetup.app/CompanionSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ff3c` | `0xa016c` | **`+0x230`** |
| `__DATA_CONST.__got` | `0xd68` | `0xd70` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1f78` | `0x1f70` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-524.0.16.0.0
+524.0.26.0.0

-  Symbols:   1258
+  Symbols:   1259
Symbols:
+ _$s17CompanionSetupKit16CSKStepPreflightC5EventO17switchMeDeviceAskyAESS_SSSgtcAEmFWC
Functions:
~ sub_100010c9c : 12 -> 72
~ sub_100010dc8 -> sub_100010e04 : 72 -> 12
~ sub_10001ef08 : 13132 -> 13260
~ sub_10004defc -> sub_10004df7c : 7916 -> 8024
~ sub_10005e804 -> sub_10005e8f0 : 1424 -> 1404
~ sub_100064d04 -> sub_100064ddc : 10516 -> 10860
```
