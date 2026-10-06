## WritingToolsAppIntentsExtension

> `/System/Library/ExtensionKit/Extensions/WritingToolsAppIntentsExtension.appex/WritingToolsAppIntentsExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x71be8` | `0x72b6c` | **`+0xf84`** |
| `__DATA.__bss` | `0xb410` | `0xb710` | **`+0x300`** |
| `__TEXT.__const` | `0x8294` | `0x8424` | **`+0x190`** |
| `__TEXT.__oslogstring` | `0xf35` | `0x1095` | **`+0x160`** |
| `__TEXT.__objc_methname` | `0x1f18` | `0x1f98` | **`+0x80`** |
| `__TEXT.__objc_stubs` | `0x6e0` | `0x760` | **`+0x80`** |
| `__TEXT.__swift5_typeref` | `0x22b8` | `0x2320` | **`+0x68`** |
| `__DATA.__data` | `0x7ab0` | `0x7b00` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x40b8` | `0x40e8` | **`+0x30`** |
| `__TEXT.__swift5_assocty` | `0x650` | `0x680` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x2bb0` | `0x2bd8` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x800` | `0x828` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x2c88` | `0x2cb0` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1f08` | `0x1f30` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x348` | `0x368` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1816` | `0x17f6` | **`-0x20`** |
| `__TEXT.__swift5_reflstr` | `0x2077` | `0x2057` | **`-0x20`** |
| `__TEXT.__swift5_proto` | `0x5b4` | `0x5cc` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x104` | `0x118` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0xf60` | `0xf70` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a64` | `0x1a74` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x188` | `0x18c` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0xc4` | `0xc8` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xd8` | `0xdc` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`

### Other Changes

```diff

-139.0.0.0.0
+143.0.0.0.0

-  Functions: 2616
-  Symbols:   283
-  CStrings:  597
+  Functions: 2632
+  Symbols:   286
+  CStrings:  603
Symbols:
+ _OBJC_CLASS_$_TCAttributedStringDigest
+ _OBJC_CLASS_$_TCAttributedStringFormatOptions
+ _TCFormatFeatureDefault
+ _TCFormatFeatureUnderline
- _objc_retain_x28
CStrings:
+ "Clamped skipped range to attributedText length %ld; requested end %ld exceeds it (context.range = %s)"
+ "Clamped trailing skipped range to attributedText length %ld; context.range max %ld exceeds it (context.range = %s)"
+ "Skipping trailing fill; skipped range start %ld is beyond attributedText length %ld (context.range = %s)"
+ "initWithAttributedString:formatOptions:"
+ "initWithOptions:"
+ "initWithUnsignedInteger:"
+ "reconstituteAttributedStringFromFormattedString:"
- "DisableInvisibleTextWorkaround"
```
