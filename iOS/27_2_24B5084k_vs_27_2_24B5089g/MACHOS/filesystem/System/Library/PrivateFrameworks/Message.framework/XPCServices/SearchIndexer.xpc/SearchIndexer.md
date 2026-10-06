## SearchIndexer

> `/System/Library/PrivateFrameworks/Message.framework/XPCServices/SearchIndexer.xpc/SearchIndexer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x490b94` | `0x492a80` | **`+0x1eec`** |
| `__TEXT.__eh_frame` | `0x121e0` | `0x12300` | **`+0x120`** |
| `__DATA.__bss` | `0x48c30` | `0x48d30` | **`+0x100`** |
| `__TEXT.__const` | `0x5fd78` | `0x5fde8` | **`+0x70`** |
| `__DATA_CONST.__auth_ptr` | `0xc0a0` | `0xc0f8` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0xd6e0` | `0xd738` | **`+0x58`** |
| `__TEXT.__swift5_typeref` | `0xc21e` | `0xc25a` | **`+0x3c`** |
| `__DATA_CONST.__const` | `0x3ef08` | `0x3ef30` | **`+0x28`** |
| `__DATA.__data` | `0x116f0` | `0x11710` | **`+0x20`** |
| `__TEXT.__cstring` | `0x71eb` | `0x720b` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0xf745` | `0xf765` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0xda90` | `0xdaa0` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x2500` | `0x2508` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-3901.200.34.0.0
+3901.200.41.0.0

-  Functions: 19949
+  Functions: 19969

-  CStrings:  2997
+  CStrings:  2998
CStrings:
+ "[%.*hhx-%{public}s] Did enable capabilities: %{public}s"
+ "[%.*hhx-%{public}s] Received post-auth capabilities from server: %{public}s"
+ "enablingCapabilities"
+ "unauthenticated(enablingCapabilities)"
- "[%.*hhx-%{public}s] Did enable UIDONLY"
- "[%.*hhx-%{public}s] Received capabilities from server"
- "unauthenticated(enablingUIDOnly)"
```
