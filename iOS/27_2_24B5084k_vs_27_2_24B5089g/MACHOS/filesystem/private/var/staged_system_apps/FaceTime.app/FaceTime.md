## FaceTime

> `/private/var/staged_system_apps/FaceTime.app/FaceTime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__auth_stubs` | `0x2fd0` | `0x2ff0` | **`+0x20`** |
| `__TEXT.__text` | `0xc5d84` | `0xc5da4` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x17f8` | `0x1808` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3077.200.51.2.1
+3077.200.64.2.3

-  Symbols:   1498
+  Symbols:   1500
Symbols:
+ _$s10CallsAppUI21VoicemailSpamReporterC6sharedACvgZ
+ _$s10CallsAppUI21VoicemailSpamReporterCMa
+ _$s10CallsAppUI29VoicemailDetailViewControllerC4item7appType12deleteAction08callbackL010didDismiss12spamReporter07contactefG0AC0aB8Services11RecentsItemV_AA0bJ0OyyYacyycySo06UIViewG0CcSgAA0d4SpamQ0CAQSgSo9CNContactCctcfc
- _$s10CallsAppUI29VoicemailDetailViewControllerC4item7appType12deleteAction08callbackL010didDismiss07contactefG0AC0aB8Services11RecentsItemV_AA0bJ0OyyYacyycySo06UIViewG0CcSgAPSgSo9CNContactCctcfc
Functions:
~ sub_1000ae0bc : 656 -> 688
```
