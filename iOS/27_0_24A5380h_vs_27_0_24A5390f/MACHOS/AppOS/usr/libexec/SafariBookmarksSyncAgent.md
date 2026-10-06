## SafariBookmarksSyncAgent

> `/usr/libexec/SafariBookmarksSyncAgent`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfcdb4` | `0xffb14` | **`+0x2d60`** |
| `__TEXT.__oslogstring` | `0x194fc` | `0x1988c` | **`+0x390`** |
| `__TEXT.__eh_frame` | `0x1920` | `0x19e8` | **`+0xc8`** |
| `__TEXT.__auth_stubs` | `0x1db0` | `0x1de0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x7ba0` | `0x7bc8` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0xef0` | `0xf08` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x3cb8` | `0x3cd0` | **`+0x18`** |
| `__TEXT.__swift5_capture` | `0x4dc` | `0x4f0` | **`+0x14`** |
| `__TEXT.__swift_as_cont` | `0x178` | `0x180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-7625.1.22.10.3
+7625.1.24.10.1

-  Functions: 4413
-  Symbols:   948
-  CStrings:  5591
+  Functions: 4420
+  Symbols:   951
+  CStrings:  5607
Symbols:
+ _$sSS21_builtinStringLiteral17utf8CodeUnitCount7isASCIISSBp_BwBi1_tcfC
+ _$sSo13os_log_type_ta0A0E7defaultABvgZ
+ _WBSOSLogMagicExtensionsSync
CStrings:
+ "Create zone if needed in %s"
+ "Deleting extension with identifier %s in %s"
+ "Did decompress extension folder for extension with ID %s in %s"
+ "Did finish handling record batch, saving change token %@ with %s"
+ "Did receive record delete for extension with ID %s in %s"
+ "Did receive record update for extension with ID %s in %s"
+ "Extension with ID %s conflicts with server record, updating local record in %s"
+ "Extension with ID %s conflicts with server record, updating remote record in %s"
+ "Extension with ID %s was deleted remotely, deleting local record in %s"
+ "Fetch remote changes in %s"
+ "Ignoring root record with %{public}@"
+ "Invalid extension with identifier %s in %s"
+ "Push local changes in %s"
+ "Restart synchronization from scratch in %s"
+ "Saving extension batch with %ld updates and %ld deletions in %s"
+ "Updating extension with identifier %s, generation: %@ in %s"
```
