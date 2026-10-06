## JournalNotifications

> `/System/Library/PreferenceBundles/JournalNotifications.bundle/JournalNotifications`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa6418` | `0xa6448` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1139` | `0x1159` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1390` | `0x13a0` | **`+0x10`** |

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
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-94.0.0.0.0
+99.2.1.0.0
Functions:
~ sub_4f7c : 6324 -> 6384
~ sub_6830 -> sub_686c : 708 -> 716
~ sub_ed58 -> sub_ed9c : 796 -> 784
~ sub_f79c -> sub_f7d4 : 1444 -> 1436
CStrings:
+ "JournalEntryAssetFileAttachmentMO is missing filePath, likely not downloaded yet. ID: %{public}s"
- "JournalEntryAssetFileAttachmentMO is missing filePath. ID: %{public}s"
```
