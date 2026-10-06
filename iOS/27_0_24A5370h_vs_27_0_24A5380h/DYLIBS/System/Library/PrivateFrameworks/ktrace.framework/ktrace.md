## ktrace

> `/System/Library/PrivateFrameworks/ktrace.framework/ktrace`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xc7608` | `0xc77f4` | **`+0x1ec`** |
| `__TEXT.__cstring` | `0x6b64` | `0x6bd4` | **`+0x70`** |
| `__TEXT.__eh_frame` | `0x2d4c` | `0x2d7c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x2c70` | `0x2c98` | **`+0x28`** |
| `__AUTH.__data` | `0x1410` | `0x1420` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3164` | `0x3170` | **`+0xc`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-703.0.0.0.0
+706.0.1.0.0

-  Functions: 3967
+  Functions: 3968

-  CStrings:  1439
+  CStrings:  1441
CStrings:
+ "\n    Available providers: "
+ "Target the command run by trace (exclude other non-targeted processes)."
+ "save trace data to a file, according to a plan"
- "save trace data to a file, according to a plan\n"
```
