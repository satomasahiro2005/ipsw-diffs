## MapsIntents

> `/System/Library/ExtensionKit/Extensions/MapsIntents.appex/MapsIntents`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x602a4` | `0x6071c` | **`+0x478`** |
| `__DATA_CONST.__const` | `0x2008` | `0x2118` | **`+0x110`** |
| `__TEXT.__const` | `0x5254` | `0x5324` | **`+0xd0`** |
| `__DATA.__bss` | `0x86c0` | `0x8740` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x4120` | `0x41a0` | **`+0x80`** |
| `__DATA.__data` | `0x2120` | `0x2190` | **`+0x70`** |
| `__TEXT.__constg_swiftt` | `0x83c` | `0x8a4` | **`+0x68`** |
| `__TEXT.__auth_stubs` | `0x2050` | `0x20b0` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0xcd0` | `0xd20` | **`+0x50`** |
| `__DATA_CONST.__auth_ptr` | `0xac0` | `0xb00` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x1038` | `0x1068` | **`+0x30`** |
| `__DATA.__common` | `0x158` | `0x170` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x838` | `0x850` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x1708` | `0x1720` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x13eb` | `0x13fb` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6c0` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xb8` | `0xc0` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x430` | `0x434` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__oslogstring`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2972.31.6.17.20
+2972.31.6.17.31

-  Functions: 1624
-  Symbols:   298
+  Functions: 1646
+  Symbols:   301
Symbols:
+ _swift_retain_x26
+ _swift_retain_x28
+ _swift_retain_x8
CStrings:
+ "CalculateETAIntent: paired watch size unavailable; using fallback contentWidth=%s mapViewportSize=%s"
- "CalculateETAIntent: paired watch size unavailable; using fallback maxContentWidth=%f mapViewportSize=%s"
```
