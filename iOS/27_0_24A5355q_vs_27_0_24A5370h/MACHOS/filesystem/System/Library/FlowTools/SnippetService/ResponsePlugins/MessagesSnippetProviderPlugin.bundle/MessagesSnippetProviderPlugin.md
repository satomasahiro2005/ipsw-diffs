## MessagesSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MessagesSnippetProviderPlugin.bundle/MessagesSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24b1c` | `0x26c7c` | **`+0x2160`** |
| `__TEXT.__eh_frame` | `0x10d0` | `0x1248` | **`+0x178`** |
| `__TEXT.__const` | `0xb48` | `0xc78` | **`+0x130`** |
| `__DATA.__bss` | `0x530` | `0x5c0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x1427` | `0x14a7` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x678` | `0x6d8` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x4b0` | `0x4d8` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x1e40` | `0x1e60` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x148` | `0x164` | **`+0x1c`** |
| `__TEXT.__swift5_fieldmd` | `0xf0` | `0x10c` | **`+0x1c`** |
| `__TEXT.__swift_as_entry` | `0x98` | `0xb4` | **`+0x1c`** |
| `__DATA.__data` | `0x478` | `0x490` | **`+0x18`** |
| `__TEXT.__swift5_assocty` | `0x78` | `0x90` | **`+0x18`** |
| `__TEXT.__swift_as_ret` | `0xa0` | `0xb8` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0xf28` | `0xf38` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x95` | `0xa5` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0xa8` | `0xb8` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x3d0` | `0x3d8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x340` | `0x348` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x371` | `0x377` | **`+0x6`** |
| `__TEXT.__swift5_proto` | `0x28` | `0x2c` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x24` | `0x28` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__swift5_capture`

### Other Changes

```diff

-3600.41.21.1.1
+3600.47.5.0.0

-  Functions: 688
+  Functions: 714

-  CStrings:  103
+  CStrings:  105
Symbols:
+ _objc_release_x27
- _swift_release_x28
CStrings:
+ "#UnsendMessageSnippetHandler %s ERROR - Failed to build plugin model: %s"
+ "#UnsendMessageSnippetHandler SUPPORTED"
```
