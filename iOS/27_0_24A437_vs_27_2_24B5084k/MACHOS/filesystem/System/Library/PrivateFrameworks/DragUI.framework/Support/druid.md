## druid

> `/System/Library/PrivateFrameworks/DragUI.framework/Support/druid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2efac` | `0x2f254` | **`+0x2a8`** |
| `__TEXT.__oslogstring` | `0x2b8a` | `0x2c66` | **`+0xdc`** |
| `__TEXT.__auth_stubs` | `0xe80` | `0xe90` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x750` | `0x758` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xd38` | `0xd40` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-9127.0.77.0.0
+9127.1.5.0.0

-  Functions: 1369
-  Symbols:   391
-  CStrings:  2743
+  Functions: 1374
+  Symbols:   392
+  CStrings:  2745
Symbols:
+ _PBCannotLoadRepresentationError
CStrings:
+ "Cannot clone file provider data to URL %@: the source URL wrapper has no URL. Relinquishing without coordinating."
+ "File provider-backed representation of type %{public}@ has neither an FPItem nor a URL. Failing the load."
```
