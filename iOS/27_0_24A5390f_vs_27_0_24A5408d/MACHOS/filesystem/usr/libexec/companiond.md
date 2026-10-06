## companiond

> `/usr/libexec/companiond`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8bffc` | `0x8c560` | **`+0x564`** |
| `__TEXT.__cstring` | `0x2669` | `0x2621` | **`-0x48`** |
| `__TEXT.__objc_methname` | `0x6115` | `0x6155` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x43a0` | `0x43e0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x417e` | `0x4142` | **`-0x3c`** |
| `__DATA_CONST.__cfstring` | `0x1ba0` | `0x1b80` | **`-0x20`** |
| `__TEXT.__const` | `0x2096` | `0x20b6` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0xc9f` | `0xcbb` | **`+0x1c`** |
| `__DATA.__data` | `0x1e20` | `0x1e10` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x1530` | `0x1540` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x2d80` | `0x2d70` | **`-0x10`** |
| `__DATA_CONST.__auth_got` | `0x16d0` | `0x16c8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-524.0.38.0.0
+524.0.56.0.0

-  Functions: 2295
-  Symbols:   1274
-  CStrings:  1952
+  Functions: 2296
+  Symbols:   1273
+  CStrings:  1950
Symbols:
- __os_feature_enabled_impl
CStrings:
+ "initWithUnsignedLongLong:"
+ "numberWithUnsignedLongLong:"
- "Feature flag not enabled."
- "Rejecting Incoming Calls session: Feature flag not enabled."
- "TelephonyUtilities"
- "telephonyCallNotifications"
```
