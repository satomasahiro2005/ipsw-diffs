## BuddyMigrator

> `/System/Library/DataClassMigrators/BuddyMigrator.migrator/BuddyMigrator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x263a8` | `0x267ec` | **`+0x444`** |
| `__TEXT.__oslogstring` | `0x2af1` | `0x2b11` | **`+0x20`** |
| `__DATA.__data` | `0x1028` | `0x1038` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x428` | `0x438` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1060` | `0x1070` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xb2a` | `0xb38` | **`+0xe`** |
| `__DATA_CONST.__auth_got` | `0x840` | `0x848` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb40` | `0xb48` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
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

### Other Changes

```diff

-5403.100.0.0.0
+5405.0.0.0.0

-  Functions: 858
-  Symbols:   404
-  CStrings:  1120
+  Functions: 860
+  Symbols:   403
+  CStrings:  1121
Symbols:
- _swift_release_x22
CStrings:
+ "Siri completion status: %s"
```
