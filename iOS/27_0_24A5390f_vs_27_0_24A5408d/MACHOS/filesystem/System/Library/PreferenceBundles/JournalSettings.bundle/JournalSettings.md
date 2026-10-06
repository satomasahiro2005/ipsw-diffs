## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74ee8` | `0x74f18` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x10a5` | `0x10c5` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xeb8` | `0xec8` | **`+0x10`** |

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
~ sub_2fad8 : 796 -> 784
~ sub_31214 -> sub_31208 : 1444 -> 1436
~ sub_3d2d0 -> sub_3d2bc : 6324 -> 6384
~ sub_3eb84 -> sub_3ebac : 708 -> 716
CStrings:
+ "JournalEntryAssetFileAttachmentMO is missing filePath, likely not downloaded yet. ID: %{public}s"
- "JournalEntryAssetFileAttachmentMO is missing filePath. ID: %{public}s"
```
