## NTKCustomization

> `/System/Library/NanoPreferenceBundles/Customization/NTKCustomization.bundle/NTKCustomization`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf958` | `0xf850` | **`-0x108`** |
| `__TEXT.__objc_stubs` | `0x3840` | `0x3800` | **`-0x40`** |
| `__TEXT.__objc_methname` | `0x5248` | `0x520f` | **`-0x39`** |
| `__DATA_CONST.__objc_intobj` | `0x18` | `—` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x1598` | `0x1588` | **`-0x10`** |
| `__TEXT.__cstring` | `0xaf4` | `0xae4` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x480` | `0x478` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2483.480.0.4.0
+2483.493.1.0.0

-  Symbols:   330
-  CStrings:  1180
+  Symbols:   329
+  CStrings:  1178
Symbols:
- _OBJC_CLASS_$_NSConstantIntegerNumber
Functions:
~ sub_3644 -> sub_35f4 : 280 -> 276
~ sub_75d0 -> sub_757c : 212 -> 196
~ sub_8c04 -> sub_8ba0 : 624 -> 392
~ sub_9b3c -> sub_99f0 : 3052 -> 3036
~ sub_adac -> sub_ac50 : 632 -> 648
~ sub_cd3c -> sub_cbf0 : 520 -> 516
~ sub_cf44 -> sub_cdf4 : 344 -> 340
~ sub_daf8 -> sub_d9a4 : 488 -> 484
CStrings:
- "setFaceSnapshotMode:"
- "setShowContentForUnadornedSnapshot:"
```
