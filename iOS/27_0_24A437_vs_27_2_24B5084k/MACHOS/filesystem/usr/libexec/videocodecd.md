## videocodecd

> `/usr/libexec/videocodecd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1ac` | `0x34c` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x33` | `0xcc` | **`+0x99`** |
| `__DATA.__common` | `—` | `0x10` | **`+0x10`** |
| `__TEXT.__const` | `0x8` | `0x10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3350.77.1.6.0
+3385.7.1.0.0

-  CStrings:  5
+  CStrings:  7
Functions:
~ sub_100000960 -> sub_1000009f8 : 428 -> 844
CStrings:
+ "<<<< videocodecd >>>> %s: Failed to elevate inactive jetsam priority, error: %d"
+ "<<<< videocodecd >>>> %s: Succeeded to elevate inactive jetsam priority."
```
