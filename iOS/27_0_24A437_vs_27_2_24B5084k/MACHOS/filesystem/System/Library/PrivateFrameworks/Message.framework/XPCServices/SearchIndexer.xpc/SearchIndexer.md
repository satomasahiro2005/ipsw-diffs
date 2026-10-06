## SearchIndexer

> `/System/Library/PrivateFrameworks/Message.framework/XPCServices/SearchIndexer.xpc/SearchIndexer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4879f0` | `0x490b94` | **`+0x91a4`** |
| `__DATA_CONST.__const` | `0x3eb50` | `0x3ef08` | **`+0x3b8`** |
| `__TEXT.__eh_frame` | `0x11e70` | `0x121e0` | **`+0x370`** |
| `__DATA.__bss` | `0x489b0` | `0x48c30` | **`+0x280`** |
| `__DATA.__data` | `0x11498` | `0x116f0` | **`+0x258`** |
| `__TEXT.__const` | `0x5fb78` | `0x5fd78` | **`+0x200`** |
| `__TEXT.__swift5_fieldmd` | `0x125b0` | `0x12714` | **`+0x164`** |
| `__TEXT.__swift5_capture` | `0x3db0` | `0x3ef0` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0xd960` | `0xda90` | **`+0x130`** |
| `__TEXT.__unwind_info` | `0xd5c0` | `0xd6e0` | **`+0x120`** |
| `__TEXT.__swift5_typeref` | `0xc108` | `0xc21e` | **`+0x116`** |
| `__TEXT.__cstring` | `0x713b` | `0x71eb` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0xf7e5` | `0xf745` | **`-0xa0`** |
| `__DATA_CONST.__auth_ptr` | `0xc030` | `0xc0a0` | **`+0x70`** |
| `__TEXT.__auth_stubs` | `0x4430` | `0x4490` | **`+0x60`** |
| `__TEXT.__constg_swiftt` | `0xb59c` | `0xb5f8` | **`+0x5c`** |
| `__DATA_CONST.__auth_got` | `0x2228` | `0x2258` | **`+0x30`** |
| `__DATA.__common` | `0xc51` | `0xc71` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x24ec` | `0x2500` | **`+0x14`** |
| `__DATA_CONST.__got` | `0xbd8` | `0xbe8` | **`+0x10`** |
| `__TEXT.__swift5_mpenum` | `0x7b4` | `0x7bc` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x1448` | `0x1450` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-3901.100.1.2.14
+3901.200.34.0.0

-  Functions: 19773
-  Symbols:   488
-  CStrings:  2993
+  Functions: 19949
+  Symbols:   489
+  CStrings:  2997
Symbols:
+ _swift_release_x11
CStrings:
+ "$hasnoattachment"
+ "Couldn't parse JMAPACCESS URL"
+ "Invalid JMAPACCESS URL"
+ "criteria charset key returnOptions "
+ "mailbox %s, count %ld, isLast: %{bool}d"
+ "untagged(jmapAccess)"
- "[%.*hhx-%{public}s] [{%.*hx}-%{sensitive,mask.mailbox}s] Completed SEARCH for boundary IDs, but didn’t get any result from the server."
- "mailbox %{sensitive,mask.mailbox}s, count %ld, isLast: %{bool}d"
```
