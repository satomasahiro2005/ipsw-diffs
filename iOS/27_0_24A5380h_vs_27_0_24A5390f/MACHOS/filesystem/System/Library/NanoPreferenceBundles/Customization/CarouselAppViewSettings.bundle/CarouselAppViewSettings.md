## CarouselAppViewSettings

> `/System/Library/NanoPreferenceBundles/Customization/CarouselAppViewSettings.bundle/CarouselAppViewSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x241e8` | `0x22d08` | **`-0x14e0`** |
| `__TEXT.__oslogstring` | `0x1750` | `0x13b3` | **`-0x39d`** |
| `__TEXT.__gcc_except_tab` | `0x2cfc` | `0x2ab4` | **`-0x248`** |
| `__DATA_CONST.__cfstring` | `0xec0` | `0xea0` | **`-0x20`** |
| `__TEXT.__cstring` | `0xa6f` | `0xa54` | **`-0x1b`** |
| `__TEXT.__unwind_info` | `0xfd0` | `0xfb8` | **`-0x18`** |
| `__TEXT.__const` | `0x398` | `0x3a8` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1115.0.97.0.0
+1115.0.101.0.0

-  Functions: 777
+  Functions: 764

-  CStrings:  1354
+  CStrings:  1323
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
