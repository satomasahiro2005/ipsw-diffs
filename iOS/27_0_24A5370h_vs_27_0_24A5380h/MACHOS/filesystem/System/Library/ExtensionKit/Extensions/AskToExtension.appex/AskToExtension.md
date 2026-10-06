## AskToExtension

> `/System/Library/ExtensionKit/Extensions/AskToExtension.appex/AskToExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2480` | `0x1c9c` | **`-0x7e4`** |
| `__TEXT.__auth_stubs` | `0x520` | `0x4a0` | **`-0x80`** |
| `__DATA_CONST.__auth_got` | `0x298` | `0x258` | **`-0x40`** |
| `__DATA_CONST.__const` | `0x210` | `0x1e8` | **`-0x28`** |
| `__TEXT.__unwind_info` | `0xf0` | `0xd0` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x98` | `0xb0` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0xa6` | `0x90` | **`-0x16`** |
| `__DATA_CONST.__auth_ptr` | `0xe0` | `0xd0` | **`-0x10`** |
| `__TEXT.__const` | `0x1ea` | `0x1da` | **`-0x10`** |
| `__DATA_CONST.__got` | `0x68` | `0x70` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-90.1.0.0.0
+92.0.0.0.0

-  Functions: 56
-  Symbols:   82
+  Functions: 47
+  Symbols:   75
Symbols:
- __swiftImmortalRefCount
- _memcpy
- _memmove
- _swift_getObjectType
- _swift_isUniquelyReferenced_nonNull_native
- _swift_release_x20
- _swift_unknownObjectRetain
CStrings:
+ "Creating Messages payload from pre-computed URL"
- "Generated AskTo URL: %s"
```
