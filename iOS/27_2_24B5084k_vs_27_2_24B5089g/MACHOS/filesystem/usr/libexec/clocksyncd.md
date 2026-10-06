## clocksyncd

> `/usr/libexec/clocksyncd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3bd88` | `0x3bab4` | **`-0x2d4`** |
| `__TEXT.__objc_methtype` | `0x197a` | `0x1925` | **`-0x55`** |
| `__TEXT.__objc_methname` | `0x91f3` | `0x91b0` | **`-0x43`** |
| `__TEXT.__objc_methlist` | `0x36b4` | `0x368c` | **`-0x28`** |
| `__DATA.__objc_selrefs` | `0x1dc0` | `0x1da8` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0xea8` | `0xea0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1510.7.0.0.0
+1510.8.0.0.0

-  Functions: 1544
+  Functions: 1538

-  CStrings:  2484
+  CStrings:  2480
CStrings:
+ "1510.8"
- "1510.7"
- "B24@0:8^{?={TSReplayTimestampsHeader=qQQ[13Q][16c]}^{TSReplayTimestampsTimestamp}}16"
- "dockReplayTimestamps:"
- "startReplayTimestamps:"
- "stopReplayTimestamps:"
```
