## ZoomTouch

> `/System/Library/SpringBoardPlugins/ZoomTouch.bundle/ZoomTouch`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4068` | `0x40a4` | **`+0x3c`** |
| `__TEXT.__objc_methname` | `0x108a` | `0x10b4` | **`+0x2a`** |
| `__TEXT.__objc_stubs` | `0xda0` | `0xdc0` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x500` | `0x508` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-906.0.0.0.0
+909.0.0.0.0

-  Symbols:   423
-  CStrings:  285
+  Symbols:   424
+  CStrings:  286
Symbols:
+ _objc_msgSend$setIgnoreTouchEventsForDisplayTransition:
Functions:
~ ___32-[ZOTWorkspace _setZoomEnabled:]_block_invoke_2 : 100 -> 160
CStrings:
+ "setIgnoreTouchEventsForDisplayTransition:"
```
