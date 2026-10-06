## InstalledApps

> `/System/Library/Settings/InstalledApps.settings/InstalledApps`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24430` | `0x24500` | **`+0xd0`** |
| `__TEXT.__cstring` | `0xdd1` | `0xe11` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1318` | `0x1330` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x656` | `0x666` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x624` | `0x630` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1090.0.0.0.0
+2027.0.1.0.0

-  Functions: 675
+  Functions: 676

-  CStrings:  254
+  CStrings:  256
CStrings:
+ "TVRemoteSettings"
+ "com.apple.TVRemoteApp"
```
