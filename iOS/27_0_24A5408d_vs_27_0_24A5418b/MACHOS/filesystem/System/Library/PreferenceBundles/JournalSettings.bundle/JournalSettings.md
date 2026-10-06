## JournalSettings

> `/System/Library/PreferenceBundles/JournalSettings.bundle/JournalSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x74f18` | `0x76b10` | **`+0x1bf8`** |
| `__TEXT.__eh_frame` | `0x1ae8` | `0x1c40` | **`+0x158`** |
| `__TEXT.__oslogstring` | `0x10c5` | `0x1165` | **`+0xa0`** |
| `__TEXT.__unwind_info` | `0x1568` | `0x15b0` | **`+0x48`** |
| `__DATA_CONST.__got` | `0xec8` | `0xf00` | **`+0x38`** |
| `__DATA.__common` | `0x460` | `0x478` | **`+0x18`** |
| `__DATA.__data` | `0x4778` | `0x4788` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x1e44` | `0x1e46` | **`+0x2`** |

### Same-size Content Changes

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
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-99.2.1.0.0
+99.2.2.0.0

-  Functions: 1826
+  Functions: 1836

-  CStrings:  968
+  CStrings:  971
CStrings:
+ "FUP-AVAIL journaling.FollowUpPrompts availability=%{public}s"
+ "FUP-AVAIL restricted reasons=[%{public}s]"
+ "FUP-AVAIL unavailable reasons=[%{public}s]"
```
