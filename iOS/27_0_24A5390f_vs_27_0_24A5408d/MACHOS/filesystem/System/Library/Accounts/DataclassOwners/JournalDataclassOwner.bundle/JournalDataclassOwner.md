## JournalDataclassOwner

> `/System/Library/Accounts/DataclassOwners/JournalDataclassOwner.bundle/JournalDataclassOwner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0xbbd` | `0xcfd` | **`+0x140`** |
| `__TEXT.__text` | `0xb9e4` | `0xba50` | **`+0x6c`** |
| `__DATA_CONST.__const` | `0x408` | `0x430` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xb00` | `0xaf0` | **`-0x10`** |
| `__TEXT.__const` | `0x7b8` | `0x7a8` | **`-0x10`** |
| `__DATA.__data` | `0x498` | `0x490` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x588` | `0x580` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x278` | `0x280` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x25f` | `0x259` | **`-0x6`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-94.0.0.0.0
+99.2.1.0.0

-  Symbols:   151
-  CStrings:  169
+  Symbols:   150
+  CStrings:  171
Symbols:
- _objc_retain_x24
Functions:
~ sub_36c4 : 2300 -> 2640
~ sub_4640 -> sub_4794 : 4504 -> 4336
~ sub_5818 -> sub_58c4 : 76 -> 68
~ sub_5864 -> sub_5908 : 16 -> 76
~ sub_5874 -> sub_5954 : 4 -> 16
~ sub_5878 -> sub_5964 : 68 -> 4
~ sub_6ee4 -> sub_6f90 : 1568 -> 1596
~ sub_7c04 -> sub_7ccc : 2080 -> 1988
~ sub_944c -> sub_94b8 : 84 -> 76
~ sub_94a0 -> sub_9504 : 76 -> 312
~ sub_94ec -> sub_963c : 312 -> 244
~ sub_9624 -> sub_9730 : 244 -> 116
~ sub_9718 -> sub_97a4 : 116 -> 244
~ sub_978c -> sub_9898 : 244 -> 84
CStrings:
+ "%{public}s called, but calling through to DataclassOwner.actionsForDisablingDataclass(on:forDataclass:)"
+ "%{public}s called, but calling through to DataclassOwner.actionsForEnablingDataclass(on:forDataclass:)"
+ "Error trying to mark all records as not uploaded; will attempt to flag for re-uploading on next app launch. Error: %@"
+ "Error trying to persist old account identifier: %@"
+ "Failed to delete all local data; will attempt to delete all local data on next app launch. Error: %@"
+ "Ignoring supported action %{public}@"
+ "Ignoring unsupported action .refresh, previously treated as delete"
+ "New account id differs from the one used when disabling dataclass. Resetting local sync state to fetch all Journal CloudKit data for the new account, while also forcing an upload of all local Journal data. New id: %{private,mask.hash}s, old id: %{private,mask.hash}s."
+ "No %{public}s records found"
+ "Performing DataClass action %{public}@ for account %{private,mask.hash}@"
- "%s called, but calling through to DataclassOwner.actionsForDisablingDataclass(on:forDataclass:)"
- "%s called, but calling through to DataclassOwner.actionsForEnablingDataclass(on:forDataclass:)"
- "Error trying to mark all records as not uploaded: %@"
- "Failed to delete all local data: %@"
- "Ignoring supported action %@"
- "Ignoring unsupported action %@, (though previously treated as delete)"
- "New account id differs from the one used when disabling dataclass. Resetting local sync state to fetch all Journal CloudKit data for the new account, while also forcing an upload of all local Journal data. New id: %s, old id: %s."
- "Performing DataClass action %{public}@ for account %@"
```
