## FontSettings

> `/System/Library/PreferenceBundles/FontSettings.bundle/FontSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x97894` | `0x98b78` | **`+0x12e4`** |
| `__TEXT.__swift5_typeref` | `0x5e29` | `0x5eef` | **`+0xc6`** |
| `__DATA.__data` | `0x2bd0` | `0x2c70` | **`+0xa0`** |
| `__TEXT.__auth_stubs` | `0x2d60` | `0x2dc0` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x948` | `0x980` | **`+0x38`** |
| `__DATA_CONST.__auth_got` | `0x16b8` | `0x16e8` | **`+0x30`** |
| `__TEXT.__const` | `0x39e8` | `0x3a08` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x784` | `0x7a4` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x560` | `0x580` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xdc0` | `0xdd8` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x180` | `0x188` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0xa30` | `0xa38` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-174.0.0.0.0
+176.0.0.0.0

-  Functions: 2344
-  Symbols:   231
-  CStrings:  301
+  Functions: 2368
+  Symbols:   237
+  CStrings:  302
Symbols:
+ _CGRectGetMaxY
+ _CGRectGetMinY
+ _CGRectIsNull
+ _CTLineCreateWithAttributedString
+ _CTLineGetBoundsWithOptions
+ _CTLineGetTypographicBounds
+ _OBJC_CLASS_$_NSAttributedString
- _CGRectGetHeight
CStrings:
+ "initWithString:attributes:"
```
