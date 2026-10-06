## JournalWidgetsSecure

> `/private/var/staged_system_apps/Journal.app/PlugIns/JournalWidgetsSecure.appex/JournalWidgetsSecure`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb8de0` | `0xb8e10` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x111a` | `0x113a` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x14e8` | `0x14f8` | **`+0x10`** |

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
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
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
~ sub_10005dd9c : 796 -> 784
~ sub_10005f390 -> sub_10005f384 : 1444 -> 1436
~ sub_10007eb18 -> sub_10007eb04 : 6324 -> 6384
~ sub_1000803cc -> sub_1000803f4 : 708 -> 716
CStrings:
+ "JournalEntryAssetFileAttachmentMO is missing filePath, likely not downloaded yet. ID: %{public}s"
- "JournalEntryAssetFileAttachmentMO is missing filePath. ID: %{public}s"
```
