## Metal

> `/System/Library/Frameworks/Metal.framework/Metal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x4380` | `0x4010` | **`-0x370`** |
| `__DATA_DIRTY.__objc_data` | `0x40b0` | `0x4420` | **`+0x370`** |
| `__DATA.__bss` | `0x38c` | `0x37c` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0x318` | `0x328` | **`+0x10`** |
| `__DATA.__data` | `0x4498` | `0x4490` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0xc8` | `0xd0` | **`+0x8`** |
| `__TEXT.__text` | `0x1e87cc` | `0x1e87c8` | **`-0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-382.5.4.0.0
+382.5.6.0.0
Functions:
~ -[_MTLBinaryArchive materializeEntryForKey:fileIndex:containsEntry:addEntry:] : 268 -> 264
CStrings:
+ "21:27:55"
+ "Sep 13 2026"
+ "Sep 13 2026 21:27:55"
- "01:16:28"
- "Sep  1 2026"
- "Sep  1 2026 01:16:28"
```
