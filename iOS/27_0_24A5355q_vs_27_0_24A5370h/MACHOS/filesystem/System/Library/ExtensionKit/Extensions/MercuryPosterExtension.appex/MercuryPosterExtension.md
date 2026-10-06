## MercuryPosterExtension

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/MercuryPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfba90` | `0xfc0f4` | **`+0x664`** |
| `__TEXT.__unwind_info` | `0x1b00` | `0x1bc0` | **`+0xc0`** |
| `__TEXT.__oslogstring` | `0x2765` | `0x2805` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x3071` | `0x30c1` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xf008` | `0xf030` | **`+0x28`** |
| `__DATA.__objc_const` | `0x6538` | `0x6518` | **`-0x20`** |
| `__TEXT.__const` | `0xb198` | `0xb1b8` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2d00` | `0x2d20` | **`+0x20`** |
| `__DATA.__data` | `0x5548` | `0x5538` | **`-0x10`** |
| `__TEXT.__objc_methname` | `0x7ff8` | `0x7fe8` | **`-0x10`** |
| `__TEXT.__swift5_capture` | `0x57c` | `0x58c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x410e` | `0x40fe` | **`-0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x42f0` | `0x42e4` | **`-0xc`** |
| `__DATA.__objc_selrefs` | `0x18d8` | `0x18e0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-76.0.2.0.0
+79.0.0.0.0

-  CStrings:  2109
+  CStrings:  2114
CStrings:
+ "COLOR_PICKER_PROMPT"
+ "Title for the color picker swatch"
+ "setPrompt:"
+ "unexpected salient floor > absoluteMax (handleUpdate): %f > %f"
+ "unexpected salient floor > absoluteMax (look): %f > %f"
+ "unexpected salient floor > absoluteMax (lookIdentifier): %f > %f"
- "unexpected salient floor > absoluteMax: %f > %f"
```
