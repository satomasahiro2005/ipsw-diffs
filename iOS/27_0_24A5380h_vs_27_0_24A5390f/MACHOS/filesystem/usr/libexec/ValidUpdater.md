## ValidUpdater

> `/usr/libexec/ValidUpdater`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x690c` | `0x6984` | **`+0x78`** |
| `__TEXT.__oslogstring` | `0x210` | `0x200` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-134.0.15.0.0
+134.0.18.0.0
Symbols:
+ _$s11SwiftCRLite15ValidDaemonCoreC19getUpdateBackgroundSbyFZ
- _objc_retain_x26
Functions:
~ sub_100002a88 : 1212 -> 1288
~ sub_100003360 -> sub_1000033ac : 1268 -> 1288
~ sub_100003bf8 -> sub_100003c58 : 532 -> 556
CStrings:
+ "setDownloadInitialDatabaseTask: skipping — background updates disabled"
+ "validDownload initial: skipping — background updates disabled"
+ "validDownload: skipping — background updates disabled"
- "setDownloadInitialDatabaseTask: skipping — disable_background_updates is set"
- "validDownload initial: skipping — disable_background_updates is set"
- "validDownload: skipping — disable_background_updates is set"
```
