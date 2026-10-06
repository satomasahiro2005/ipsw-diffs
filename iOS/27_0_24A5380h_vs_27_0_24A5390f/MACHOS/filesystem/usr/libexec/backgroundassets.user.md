## backgroundassets.user

> `/usr/libexec/backgroundassets.user`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5a17c` | `0x5a458` | **`+0x2dc`** |
| `__TEXT.__oslogstring` | `0x6c83` | `0x6db3` | **`+0x130`** |
| `__DATA_CONST.__cfstring` | `0x24c0` | `0x2520` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x9cc4` | `0x9c6e` | **`-0x56`** |
| `__TEXT.__cstring` | `0x41a0` | `0x41e0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x7840` | `0x7800` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0x3544` | `0x352c` | **`-0x18`** |
| `__DATA.__objc_const` | `0x5a40` | `0x5a30` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0x21b8` | `0x21a8` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-274.0.0.0.0
+279.0.1.0.0

-  CStrings:  2609
+  CStrings:  2613
CStrings:
+ "Asset pack management info: %@\n"
+ "DownloadID"
+ "Poking the scheduler because at least one download event remains undelivered to the application with the bundle identifier “%{public}@”…"
+ "Poking the scheduler because at least one download for the application with the bundle identifier “%{public}@” was promoted to the foreground…"
+ "Poking the scheduler…"
+ "Was foreground download: %@\n"
- "TB,V_wasForegroundDownload"
- "setWasForegroundDownload:"
```
