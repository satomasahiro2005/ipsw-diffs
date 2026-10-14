## AlarmUIPlugin

> `/System/Library/Snippets/UIPlugins/AlarmUIPlugin.bundle/AlarmUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b8c` | `0x3438` | **`+0x8ac`** |
| `__TEXT.__auth_stubs` | `0x460` | `0x580` | **`+0x120`** |
| `__DATA.__bss` | `0x220` | `0x320` | **`+0x100`** |
| `__TEXT.__const` | `0x2ae` | `0x342` | **`+0x94`** |
| `__DATA_CONST.__auth_got` | `0x230` | `0x2c0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `—` | `0x85` | **`+0x85`** |
| `__DATA_CONST.__auth_ptr` | `0x168` | `0x190` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x1f8` | `0x220` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x120` | `0x148` | **`+0x28`** |
| `__TEXT.__swift5_assocty` | `0x30` | `0x48` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x4e0` | `0x4f8` | **`+0x18`** |
| `__DATA.__data` | `0x248` | `0x258` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x118` | `0x128` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x51` | `0x61` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0xe0` | `0xec` | **`+0xc`** |
| `__TEXT.__swift5_proto` | `0x10` | `0x18` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-  Functions: 70
-  Symbols:   65
-  CStrings:  1
+  Functions: 84
+  Symbols:   77
+  CStrings:  2
Symbols:
+ __os_log_impl
+ __swiftImmortalRefCount
+ _memcpy
+ _memmove
+ _objc_release_x23
+ _os_log_type_enabled
+ _swift_getAtKeyPath
+ _swift_getObjectType
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
CStrings:
+ "Accessing Environment<%s>'s value outside of being installed on a View. This will always read the default value and will not update."
```
