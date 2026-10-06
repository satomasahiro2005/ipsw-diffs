## ActivityBridgeSetup

> `/System/Library/NanoPreferenceBundles/SetupBundles/ActivityBridgeSetup.bundle/ActivityBridgeSetup`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x56858` | `0x5a608` | **`+0x3db0`** |
| `__TEXT.__swift5_typeref` | `0x3bf1` | `0x4ac1` | **`+0xed0`** |
| `__TEXT.__const` | `0x3558` | `0x3a88` | **`+0x530`** |
| `__DATA.__bss` | `0x1f78` | `0x2498` | **`+0x520`** |
| `__TEXT.__auth_stubs` | `0x23b0` | `0x2690` | **`+0x2e0`** |
| `__DATA.__data` | `0x21e8` | `0x23b8` | **`+0x1d0`** |
| `__DATA_CONST.__auth_got` | `0x11e8` | `0x1358` | **`+0x170`** |
| `__DATA_CONST.__auth_ptr` | `0x838` | `0x9a0` | **`+0x168`** |
| `__DATA_CONST.__const` | `0x2378` | `0x2488` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x1300` | `0x13b8` | **`+0xb8`** |
| `__TEXT.__swift5_assocty` | `0x368` | `0x3f8` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0x1344` | `0x13c8` | **`+0x84`** |
| `__DATA_CONST.__got` | `0x908` | `0x988` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0xa48` | `0xaac` | **`+0x64`** |
| `__TEXT.__objc_stubs` | `0x3a20` | `0x3a80` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x4f45` | `0x4f85` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0xbcf` | `0xc0f` | **`+0x40`** |
| `__TEXT.__swift5_proto` | `0xe8` | `0x110` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1420` | `0x1438` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0xa0` | `0xb4` | **`+0x14`** |
| `__TEXT.__cstring` | `0x15e0` | `0x15f0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x51c` | `0x52c` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0xc0` | `0xd0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-2027.1.36.0.0
+2027.1.45.0.0

-  Functions: 1647
-  Symbols:   412
-  CStrings:  1197
+  Functions: 1734
+  Symbols:   415
+  CStrings:  1200
Symbols:
+ _UIFontDescriptorSystemDesignRounded
+ _swift_bridgeObjectRetain_n
+ _swift_coroFrameAlloc
CStrings:
+ "FITNESS_UNIT_FORMAT_NO_SPACE_BREAKABLE"
+ "fontDescriptor"
+ "fontDescriptorWithDesign:"
+ "sizeWithAttributes:"
- "FITNESS_UNIT_FORMAT_NO_SPACE"
```
