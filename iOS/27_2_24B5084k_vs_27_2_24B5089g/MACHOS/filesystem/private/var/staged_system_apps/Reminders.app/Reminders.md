## Reminders

> `/private/var/staged_system_apps/Reminders.app/Reminders`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5755ac` | `0x575674` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x137d0` | `0x13800` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x9bf8` | `0x9c10` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4076.0.0.0.0
+4077.0.0.0.0

-  Functions: 19102
-  Symbols:   8426
+  Functions: 19103
+  Symbols:   8429
Symbols:
+ _$s15RemindersUICore19TTRITextCellContentC21shouldChangeTextBlockSbSS_So8_NSRangeVSStcSgvs
+ _$s15RemindersUICore28TTRTextFieldCharacterLimiterO08isWithinE5Limit3for5range17replacementString9maxLengthSbSo012NSAttributedM0C_So8_NSRangeVSSSgSitFZ
+ _$s15RemindersUICore28TTRTextFieldCharacterLimiterO17listNameMaxLengthSivgZ
+ _$s19ReminderKitInternal15REMFeatureFlagsO15RemindersUICoreE31isMagicComposeSupportedOnDeviceSbvgZ
- _$s19ReminderKitInternal15REMFeatureFlagsO15RemindersUICoreE23isMagicComposeAvailableSbvgZ
Functions:
~ sub_1002545bc : 464 -> 492
+ sub_100254868
```
