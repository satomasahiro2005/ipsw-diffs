## feedbackd

> `/usr/libexec/feedbackd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78a0c` | `0x78f4c` | **`+0x540`** |
| `__TEXT.__oslogstring` | `0x279f` | `0x27bf` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x7d0` | `0x7e8` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x1f80` | `0x1f90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xfc8` | `0xfd0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
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
- `__TEXT.__unwind_info`

### Other Changes

```diff

-  Functions: 1451
-  Symbols:   870
-  CStrings:  755
+  Functions: 1452
+  Symbols:   873
+  CStrings:  756
Symbols:
+ _$s15FeedbackService12FBKSDonationC13DonationErrorO11unsupportedyA2EmFWC
+ _$s15FeedbackService12FBKSDonationC13DonationErrorOMa
+ _$s15FeedbackService12FBKSDonationC13DonationErrorOs0E0AAMc
CStrings:
+ "Donation not enabled"
```
