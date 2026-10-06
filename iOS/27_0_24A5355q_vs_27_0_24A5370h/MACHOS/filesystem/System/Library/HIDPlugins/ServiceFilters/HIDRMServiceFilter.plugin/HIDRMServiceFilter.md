## HIDRMServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/HIDRMServiceFilter.plugin/HIDRMServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5488` | `0x5b1c` | **`+0x694`** |
| `__TEXT.__auth_stubs` | `0x860` | `0x8e0` | **`+0x80`** |
| `__TEXT.__oslogstring` | `0x102` | `0x162` | **`+0x60`** |
| `__DATA_CONST.__auth_got` | `0x438` | `0x478` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x228` | `0x250` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x160` | `0x180` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x58` | `0x78` | **`+0x20`** |
| `__TEXT.__const` | `0x1b2` | `0x1c2` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x190` | `0x1a0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x178` | `0x180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-47.0.0.0.0
+49.0.0.0.0

-  Functions: 111
-  Symbols:   106
-  CStrings:  141
+  Functions: 116
+  Symbols:   110
+  CStrings:  143
Symbols:
+ _swift_release_n
+ _swift_release_x23
+ _swift_release_x28
+ _swift_retain_n
CStrings:
+ "Event tree analysis complete: hasUserInput: %{bool}d, allEventsSafe: %{bool}d"
+ "children"
```
