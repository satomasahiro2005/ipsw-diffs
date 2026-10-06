## NANDTaskScheduler

> `/usr/libexec/NANDTaskScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5e8` | `0xf904` | **`+0x31c`** |
| `__TEXT.__oslogstring` | `0x2f6f` | `0x2fcf` | **`+0x60`** |
| `__TEXT.__cstring` | `0x1259` | `0x12b4` | **`+0x5b`** |
| `__DATA_CONST.__cfstring` | `0xa60` | `0xa80` | **`+0x20`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-847.0.0.0.0
+849.0.5.0.0

-  CStrings:  749
+  CStrings:  753
Functions:
~ sub_10000a354 : 7544 -> 7988
~ sub_10000d95c -> sub_10000db18 : 3044 -> 3072
~ sub_10000e6a8 -> sub_10000e880 : 1228 -> 1552
CStrings:
+ "Failed to deregister bdr throughput tracking: %@"
+ "Failed to register bdr throughput tracking: %@"
+ "INVALID PING RESPONSE - STOPPING"
+ "idlestack.bdr"
```
