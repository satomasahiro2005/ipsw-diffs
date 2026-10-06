## GAXSpringboardServer

> `/System/Library/AccessibilityBundles/GAXSpringboardServer.bundle/GAXSpringboardServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__oslogstring` | `0x1ad7` | `0x1bc8` | **`+0xf1`** |
| `__TEXT.__text` | `0x16130` | `0x161dc` | **`+0xac`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1067.3.0.0.0
+1067.3.1.0.0

-  CStrings:  1596
+  CStrings:  1599
Functions:
~ sub_4394 : 300 -> 412
~ sub_452c -> sub_459c : 184 -> 244
CStrings:
+ "Guided Access is trying to make the system aperture inert, but we already have an assertion."
+ "Ignoring request for system aperture to become inert, Guided Access is not running."
+ "No system aperture inert assertion held, nothing to invalidate."
```
