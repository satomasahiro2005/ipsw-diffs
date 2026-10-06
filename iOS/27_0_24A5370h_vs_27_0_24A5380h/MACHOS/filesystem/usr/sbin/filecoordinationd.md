## filecoordinationd

> `/usr/sbin/filecoordinationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x16e8` | `0x1384` | **`-0x364`** |
| `__TEXT.__oslogstring` | `0x1e0` | `0x1aa` | **`-0x36`** |
| `__TEXT.__unwind_info` | `0xd8` | `0xc8` | **`-0x10`** |
| `__TEXT.__const` | `0x80` | `0x78` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`

### Other Changes

```diff

-5027.0.55.1.0
+5027.0.59.0.0

-  Functions: 31
+  Functions: 28

-  CStrings:  37
+  CStrings:  36
CStrings:
- "Received nspace IPC from %u for %{private}s - req: %d"
```
