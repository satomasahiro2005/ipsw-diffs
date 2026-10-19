## feedbackd

> `/usr/libexec/feedbackd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x81c48` | `0x82108` | **`+0x4c0`** |
| `__TEXT.__oslogstring` | `0x28ff` | `0x291f` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x800` | `0x818` | **`+0x18`** |
| `__DATA.__data` | `0x1d18` | `0x1d28` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2090` | `0x20a0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1050` | `0x1058` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1778` | `0x1780` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-  Functions: 1583
-  Symbols:   895
-  CStrings:  781
+  Functions: 1584
+  Symbols:   898
+  CStrings:  782
Symbols:
+ _$s15FeedbackService12FBKSDonationC13DonationErrorO11unsupportedyA2EmFWC
+ _$s15FeedbackService12FBKSDonationC13DonationErrorOMa
+ _$s15FeedbackService12FBKSDonationC13DonationErrorOs0E0AAMc
Functions:
~ sub_1000278a8 : 440 -> 1264
+ sub_100027d98
- sub_10003a8d0
+ sub_10003aff0
CStrings:
+ "Donation not enabled"
```
