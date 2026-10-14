## linkd

> `/usr/libexec/linkd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc9f8c` | `0xcb428` | **`+0x149c`** |
| `__DATA.__bss` | `0x4f80` | `0x5280` | **`+0x300`** |
| `__TEXT.__const` | `0x5c3c` | `0x5ddc` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x4ef6` | `0x4f81` | **`+0x8b`** |
| `__DATA.__data` | `0x3b90` | `0x3c10` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x2d9a` | `0x2e02` | **`+0x68`** |
| `__DATA_CONST.__auth_ptr` | `0x1420` | `0x1468` | **`+0x48`** |
| `__TEXT.__eh_frame` | `0xa370` | `0xa3b0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x27a0` | `0x27e0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x3fcd` | `0x3ffd` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x2a0` | `0x2d0` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x9b20` | `0x9b48` | **`+0x28`** |
| `__TEXT.__constg_swiftt` | `0x1d60` | `0x1d80` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x3d00` | `0x3d20` | **`+0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x16e8` | `0x1704` | **`+0x1c`** |
| `__DATA_CONST.__got` | `0xa78` | `0xa90` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0x34c` | `0x364` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x1b8` | `0x1cc` | **`+0x14`** |
| `__DATA.__objc_selrefs` | `0xe30` | `0xe40` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1325` | `0x1318` | **`-0xd`** |
| `__TEXT.__swift5_types` | `0x1cc` | `0x1d0` | **`+0x4`** |
| `__TEXT.__objc_classname` | `0x90c` | `0x909` | **`-0x3`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-301.1.15.0.0
+301.1.16.0.0

-  Functions: 5593
-  Symbols:   1199
-  CStrings:  1235
+  Functions: 5615
+  Symbols:   1202
+  CStrings:  1240
Symbols:
+ _NSURLIsExcludedFromBackupKey
+ __kCFURLIsExcludedFromCloudBackupKey
+ __kCFURLIsExcludedFromUnencryptedBackupKey
CStrings:
+ "%{public}@ already excluded from backups"
+ "Excluded %{public}@ from backups"
+ "Setting %{public}s on %{public}@"
+ "resourceValuesForKeys:error:"
+ "setResourceValues:error:"
```
