## bluetoothaudiod

> `/usr/sbin/bluetoothaudiod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a530` | `0x6a8c8` | **`+0x398`** |
| `__TEXT.__oslogstring` | `0xb071` | `0xb10b` | **`+0x9a`** |
| `__TEXT.__objc_stubs` | `0xb000` | `0xb060` | **`+0x60`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x538` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x115e3` | `0x11602` | **`+0x1f`** |
| `__DATA_CONST.__objc_intobj` | `0x150` | `0x138` | **`-0x18`** |
| `__TEXT.__objc_methlist` | `0x6670` | `0x6680` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x3a08` | `0x3a10` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2700.34.0.0.0
+2700.35.0.0.0

-  Functions: 2467
+  Functions: 2469

-  CStrings:  5010
+  CStrings:  5013
CStrings:
+ "CIS cleanup: no CIS for CIS ID %@, skipping ASE decouple and established-count update"
+ "liveDevicesForQueuedProcedure:"
+ "sortAcceptorsByRank: device %@ not a connected set member, skipping"
```
