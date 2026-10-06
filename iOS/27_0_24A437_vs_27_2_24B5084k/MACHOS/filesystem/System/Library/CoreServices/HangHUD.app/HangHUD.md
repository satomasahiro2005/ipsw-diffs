## HangHUD

> `/System/Library/CoreServices/HangHUD.app/HangHUD`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x315dc` | `0x31a34` | **`+0x458`** |
| `__TEXT.__oslogstring` | `0x51f3` | `0x5309` | **`+0x116`** |
| `__TEXT.__const` | `0x510` | `0x4e0` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x1c70` | `0x1c98` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xc70` | `0xc90` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x41c` | `0x43c` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x5c80` | `0x5c60` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0xcc0` | `0xce0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x648` | `0x658` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x1a3e` | `0x1a2f` | **`-0xf`** |
| `__TEXT.__objc_methname` | `0xa928` | `0xa91a` | **`-0xe`** |
| `__DATA.__objc_const` | `0x6c10` | `0x6c08` | **`-0x8`** |
| `__DATA.__objc_selrefs` | `0x21a8` | `0x21a0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 1558
-  Symbols:   303
-  CStrings:  3127
+  Functions: 1563
+  Symbols:   305
+  CStrings:  3130
Symbols:
+ _CFAutorelease
+ _objc_retainAutoreleasedReturnValue
CStrings:
+ "Display:%@ has no available modes (%lu modes total), dropping from display array: %@"
+ "Enumerating display:%@ of type:%ld"
+ "Failed to create a HUDContext for displayId=%u"
+ "Ignoring non-approved display:%@ due to type:%ld"
+ "Refusing to create a HUDContext with no display to render to."
+ "allTaskingPrefNames"
- "B32@0:8Q16^@24"
- "mainDisplay"
- "setCLPCTrialID:error:"
```
