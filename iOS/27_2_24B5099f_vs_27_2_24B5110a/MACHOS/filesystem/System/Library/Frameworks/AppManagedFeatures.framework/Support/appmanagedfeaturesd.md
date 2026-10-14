## appmanagedfeaturesd

> `/System/Library/Frameworks/AppManagedFeatures.framework/Support/appmanagedfeaturesd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x87c54` | `0x88a78` | **`+0xe24`** |
| `__TEXT.__cstring` | `0x148a` | `0x140a` | **`-0x80`** |
| `__TEXT.__eh_frame` | `0x673c` | `0x6774` | **`+0x38`** |
| `__TEXT.__auth_stubs` | `0x2150` | `0x2180` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x3963` | `0x3993` | **`+0x30`** |
| `__DATA_CONST.__auth_got` | `0x10b0` | `0x10c8` | **`+0x18`** |
| `__DATA_CONST.__got` | `0x840` | `0x850` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-58.40.13.0.0
+58.42.1.0.0

-  Symbols:   999
-  CStrings:  670
+  Symbols:   1004
+  CStrings:  668
Symbols:
+ _$s18AppManagedFeatures0abC5ErrorO20containerUnavailableyA2CmFWC
+ _$s18AppManagedFeatures0abC5ErrorOSQAAMc
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_retain_x8
CStrings:
+ "Failed to create container: %{public}@"
- "Failed to create container. Error: "
- "Failed to get container path"
- "appmanagedfeaturesd/FileManager+Configuration.swift"
```
