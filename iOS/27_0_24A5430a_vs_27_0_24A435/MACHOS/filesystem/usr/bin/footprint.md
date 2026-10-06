## footprint

> `/usr/bin/footprint`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x215c0` | `0x215c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```text
Functions:
~ -[FPUserProcess _enumerateDispositionChunksWithStartAddr:pagesToQuery:block:] : 392 -> 400
~ ___33-[FPUserProcess _gatherImageData]_block_invoke_2 : 1576 -> 1584
~ -[FPBootCarveout _gatherData:extendedInfoProvider:] : 4256 -> 4240
~ -[FPKernelProcess _gatherData:extendedInfoProvider:] : 2604 -> 2608
~ _enumerateObjects : 324 -> 328
```
