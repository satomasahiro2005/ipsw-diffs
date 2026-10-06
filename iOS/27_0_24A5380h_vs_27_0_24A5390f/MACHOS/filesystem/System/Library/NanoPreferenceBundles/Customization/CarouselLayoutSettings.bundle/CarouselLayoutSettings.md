## CarouselLayoutSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselLayoutSettings.bundle/CarouselLayoutSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x22da8` | `0x218c8` | **`-0x14e0`** |
| `__TEXT.__oslogstring` | `0x166d` | `0x12d0` | **`-0x39d`** |
| `__TEXT.__gcc_except_tab` | `0x2cfc` | `0x2ab4` | **`-0x248`** |
| `__TEXT.__unwind_info` | `0xf60` | `0xf38` | **`-0x28`** |
| `__DATA_CONST.__cfstring` | `0xdc0` | `0xda0` | **`-0x20`** |
| `__TEXT.__cstring` | `0x98d` | `0x972` | **`-0x1b`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1115.0.97.0.0
+1115.0.101.0.0

-  Functions: 722
+  Functions: 709

-  CStrings:  1275
+  CStrings:  1244
CStrings:
- "(final)"
- "WILL move %@ -> %s %@"
- "[343 collapse] move %@ -> %s; displaced:%@; "
- "[343 move] WILL move %@ -> %s %@"
- "[343 move] consider move %@ -> %s %@"
- "[343 move] move %@ -> %s; next:%@; "
- "[343 move] reverse enumerator ended after:%s unplacedNode:%@"
- "[_changedNodes count] %d (delegate=%@)"
- "[collapse] %s has no further occupied hexes"
- "[collapse] %s start"
- "[collapse] move %@ -> %s"
- "[less lonely] %@ fall complete"
- "[less lonely] %@ occupied (neighbors of %s)"
- "[less lonely] %s has %d neighbors (neighbors of %s)"
- "[less lonely] %s not connected (neighbors of %s)"
- "[less lonely] %s unoccupied"
- "[less lonely] move %@ -> %s"
- "[lonely %s] move %@ -> %s"
- "[lonely?] add %@"
- "[lonely?] add %@ (final)"
- "[lonely] add %@"
- "[push up] found empty: %s"
- "[push up] removed %@; move %@ -> %s"
- "[should not happen - searched from center] move %@ -> %s"
- "[simple shift] removed %@; move %@ -> %s"
- "[unoccupied] move %@ -> %s"
- "changed count:%d (delegate=%@)"
- "final"
- "intermediate"
- "removed %@"
- "reverted %@ -> %s"
```
