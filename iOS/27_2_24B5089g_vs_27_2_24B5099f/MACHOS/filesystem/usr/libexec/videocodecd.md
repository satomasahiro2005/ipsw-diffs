## videocodecd

> `/usr/libexec/videocodecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34c` | `0x1ac` | **`-0x1a0`** |
| `__TEXT.__oslogstring` | `0xcc` | `0x33` | **`-0x99`** |
| `__DATA.__common` | `0x10` | `—` | **`-0x10`** |
| `__TEXT.__const` | `0x10` | `0x8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3385.8.1.11.1
+3385.12.1.0.0

-  CStrings:  7
+  CStrings:  5
Functions:
~ sub_1000009f8 -> sub_100000960 : 844 -> 428
CStrings:
- "<<<< videocodecd >>>> %s: Failed to elevate inactive jetsam priority, error: %d"
- "<<<< videocodecd >>>> %s: Succeeded to elevate inactive jetsam priority."
```
