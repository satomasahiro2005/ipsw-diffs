## MusicSnippetProviderPlugin

> `/System/Library/FlowTools/SnippetService/ResponsePlugins/MusicSnippetProviderPlugin.bundle/MusicSnippetProviderPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3454` | `0x3f70` | **`+0xb1c`** |
| `__TEXT.__auth_stubs` | `0x4d0` | `0x570` | **`+0xa0`** |
| `__TEXT.__oslogstring` | `0x205` | `0x280` | **`+0x7b`** |
| `__DATA_CONST.__auth_got` | `0x268` | `0x2b8` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x2f` | `0x65` | **`+0x36`** |
| `__DATA.__data` | `0xd8` | `0x100` | **`+0x28`** |
| `__TEXT.__const` | `0x112` | `0x13a` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x68` | `0x88` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xb0` | `0xc0` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA_CONST.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-4026.210.18.1.0
+4026.200.22.0.0

-  Functions: 48
-  Symbols:   61
-  CStrings:  12
+  Functions: 50
+  Symbols:   63
+  CStrings:  14
Symbols:
+ _objc_release_x24
+ _objc_release_x27
Functions:
~ sub_25a8 : 5308 -> 5708
+ sub_41f0
+ sub_5244
CStrings:
+ "%{public}s Unsupported subtitle type: %{public}s, using nil"
+ "%{public}s lazy subtitle: %{public}s, using nil"
```
