## hangtracerd

> `/usr/libexec/hangtracerd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x36f48` | `0x37844` | **`+0x8fc`** |
| `__TEXT.__oslogstring` | `0x6779` | `0x69bc` | **`+0x243`** |
| `__DATA_CONST.__cfstring` | `0x6500` | `0x6560` | **`+0x60`** |
| `__TEXT.__objc_stubs` | `0x5ca0` | `0x5d00` | **`+0x60`** |
| `__TEXT.__objc_methname` | `0x9c5b` | `0x9c9a` | **`+0x3f`** |
| `__TEXT.__cstring` | `0x4da0` | `0x4dde` | **`+0x3e`** |
| `__TEXT.__const` | `0x430` | `0x400` | **`-0x30`** |
| `__DATA_CONST.__const` | `0x2238` | `0x2260` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1ef8` | `0x1f18` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x430` | `0x450` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xfa0` | `0xfb0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xbe0` | `0xbf0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x7e0` | `0x7e8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x289c` | `0x28a4` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-426.0.0.0.0
+430.0.0.0.0

-  Functions: 1386
-  Symbols:   402
-  CStrings:  3160
+  Functions: 1396
+  Symbols:   403
+  CStrings:  3175
Symbols:
+ _objc_retainAutoreleasedReturnValue
CStrings:
+ "%s: unable to resolve process path for pid %d, App launch request type"
+ ".."
+ "/"
+ "Display:%@ has no available modes (%lu modes total), dropping from display array: %@"
+ "Enumerating display:%@ of type:%ld"
+ "HANGTRACER_XPC_NAME_KEY for pid %d is missing or exceeds %d bytes; using fallback identifier"
+ "HANGTRACER_XPC_STATE_INFO_KEY data for pid %d is %zu bytes, expected exactly %zu; ignoring"
+ "HANGTRACER_XPC_USER_ACTION_DATA_KEY for pid %d is %zu bytes, exceeding limit of %d; ignoring"
+ "Ignoring non-approved display:%@ due to type:%ld"
+ "Refusing to create a HUDContext with no display to render to."
+ "allTaskingPrefNames"
+ "arrayWithCapacity:"
+ "availableModes"
+ "com.apple.chrono.WidgetRenderer-"
+ "displayType"
+ "displays"
+ "processPath is nil for App launch request type"
- "WidgetRenderer-Default"
- "mainDisplay"
```
