## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/CloudDocs`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x16d0` | `0x1270` | **`-0x460`** |
| `__DATA_DIRTY.__objc_data` | `0x820` | `0xc80` | **`+0x460`** |
| `__TEXT.__text` | `0x7ea40` | `0x7e998` | **`-0xa8`** |
| `__TEXT.__cstring` | `0xb8ea` | `0xb8d0` | **`-0x1a`** |
| `__DATA_DIRTY.__data` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x8d78` | `0x8d68` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x2660` | `0x2670` | **`+0x10`** |
| `__AUTH.__data` | `0xc8` | `0xc0` | **`-0x8`** |
| `__DATA.__data` | `0xd30` | `0xd28` | **`-0x8`** |

### Other Changes

```diff

-5168.40.149.0.1
+5168.40.162.0.0

-  Functions: 3045
+  Functions: 3046
CStrings:
+ "5168.40.162"
+ "App library not found"
+ "Client zone not found"
+ "Invalid parameter '%@'"
+ "Unknown key"
+ "[CRIT] UNREACHABLE: encoded object has bogus mangledID%@"
+ "[CRIT] UNREACHABLE: invalid mangled string%@"
+ "[CRIT] UNREACHABLE: invalid zone or owner name%@"
+ "[CRIT] UNREACHABLE: malformed alias target%@"
- "5168.40.149.0.1"
- "App library not found: '%@'"
- "Client zone not found: '%@'"
- "Invalid parameter '%@': %@"
- "Unknown key: '%@'"
- "[CRIT] UNREACHABLE: encoded object has bogus mangledID %@%@"
- "[CRIT] UNREACHABLE: invalid mangled string %@%@"
- "[CRIT] UNREACHABLE: invalid zone %@ or owner name %@%@"
- "[CRIT] UNREACHABLE: malformed alias target: %@%@"
```
