## sharereportingd

> `/usr/libexec/sharereportingd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x40ca0` | `0x4475c` | **`+0x3abc`** |
| `__TEXT.__eh_frame` | `0x3310` | `0x3750` | **`+0x440`** |
| `__TEXT.__const` | `0x3888` | `0x3a68` | **`+0x1e0`** |
| `__TEXT.__cstring` | `0x26d7` | `0x2837` | **`+0x160`** |
| `__DATA_CONST.__const` | `0x2798` | `0x28e8` | **`+0x150`** |
| `__TEXT.__unwind_info` | `0x1398` | `0x1490` | **`+0xf8`** |
| `__TEXT.__auth_stubs` | `0x1400` | `0x1470` | **`+0x70`** |
| `__TEXT.__swift5_reflstr` | `0x873` | `0x8e3` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0xd90` | `0xdec` | **`+0x5c`** |
| `__TEXT.__constg_swiftt` | `0xbdc` | `0xc2c` | **`+0x50`** |
| `__TEXT.__swift_as_cont` | `0x250` | `0x290` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0xa08` | `0xa40` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0xb89` | `0xbbd` | **`+0x34`** |
| `__TEXT.__swift_as_ret` | `0x178` | `0x1ac` | **`+0x34`** |
| `__DATA.__data` | `0x17c0` | `0x17f0` | **`+0x30`** |
| `__DATA_CONST.__auth_ptr` | `0x300` | `0x330` | **`+0x30`** |
| `__TEXT.__swift5_capture` | `0x3f8` | `0x424` | **`+0x2c`** |
| `__DATA.__objc_const` | `0x880` | `0x8a8` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x2e7` | `0x307` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x2c8` | `0x2e4` | **`+0x1c`** |
| `__TEXT.__swift5_builtin` | `0x14` | `0x28` | **`+0x14`** |
| `__TEXT.__swift_as_entry` | `0xd4` | `0xe0` | **`+0xc`** |
| `__DATA.__common` | `0xa8` | `0xb0` | **`+0x8`** |
| `__DATA.__objc_data` | `0x3c8` | `0x3d0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x280` | `0x288` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xe8` | `0xf0` | **`+0x8`** |
| `__TEXT.__objc_methname` | `0x864` | `0x85e` | **`-0x6`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-89.0.0.0.0
+92.0.0.0.0

-  Functions: 1357
-  Symbols:   483
-  CStrings:  374
+  Functions: 1406
+  Symbols:   494
+  CStrings:  384
Symbols:
+ _$s2os21OSAllocatedUnfairLockVMn
+ _$sSh11descriptionSSvg
+ _$sSy10FoundationE23removingPercentEncodingSSSgvg
+ _$ss13ManagedBufferCMn
+ _$ss5print_9separator10terminatoryypd_S2StF
+ _$ss6UInt32VMn
+ _OBJC_CLASS_$_NSString
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_getForeignTypeMetadata
+ _swift_retain_x25
CStrings:
+ " = excluded.reportDate,\n    "
+ " = excluded.uploadedReportIdentifier"
+ ", uploadedReportIdentifier="
+ "Checked for any registered URLs. { hasAny="
+ "Checking if any URLs are registered."
+ "Failed to upload share junk report record."
+ "Failed to upload share junk report record. { record="
+ "Has any registered URLs result. { hasAny="
+ "allowlist"
+ "hasAnyRegisteredURLsWithCompletionHandler:"
+ "uploadedReportIdentifier"
+ "v24@0:8@?16"
+ "v24@0:8@?<v@?B@\"NSError\">16"
- " = excluded.reportDate"
- "$__lazy_storage_$_allowlist"
- ")\nVALUES (?, ?, ?)\nON CONFLICT("
```
