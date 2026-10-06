## RCS

> `/System/Library/Messages/PlugIns/RCS.imservice/RCS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10fcc0` | `0x1108f0` | **`+0xc30`** |
| `__TEXT.__objc_stubs` | `0x5800` | `0x5900` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0xa8c0` | `0xa978` | **`+0xb8`** |
| `__TEXT.__objc_methname` | `0x6073` | `0x6103` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x69a8` | `0x69f8` | **`+0x50`** |
| `__DATA.__objc_selrefs` | `0x18f8` | `0x1938` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3bd8` | `0x3c10` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x9b8` | `0x9c8` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x21f3` | `0x21e7` | **`-0xc`** |
| `__TEXT.__swift_as_cont` | `0x99c` | `0x9a8` | **`+0xc`** |
| `__TEXT.__swift_as_ret` | `0x330` | `0x33c` | **`+0xc`** |
| `__DATA.__data` | `0x3cc0` | `0x3cc8` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1590` | `0x1588` | **`-0x8`** |
| `__TEXT.__constg_swiftt` | `0x244c` | `0x2454` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x2b8` | `0x2c0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1483.100.10.2.4
+1486.100.5.2.1

-  Functions: 3883
-  Symbols:   490
-  CStrings:  1676
+  Functions: 3888
+  Symbols:   492
+  CStrings:  1685
Symbols:
+ _OBJC_CLASS_$_IMMessagePartDescriptor
+ _OBJC_CLASS_$_IMMessagePartGUID
CStrings:
+ "Ignoring send failure (error %u) for %s; message already delivered/read"
+ "defaultPrefix"
+ "encodedMessagePartGUID"
+ "initWithMessageGUID:prefix:partNumber:"
+ "isDelivered"
+ "isRead"
+ "messagePartIndex"
+ "messageParts"
+ "setSupportsReplies:"
```
