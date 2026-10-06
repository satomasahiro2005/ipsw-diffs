## IOMFB_FDR_Loader

> `/usr/bin/IOMFB_FDR_Loader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34b08` | `0x34b58` | **`+0x50`** |
| `__TEXT.__cstring` | `0x8fa2` | `0x8fea` | **`+0x48`** |

### Same-size Content Changes

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-700.50.104.1.0
+700.50.108.0.0
Functions:
~ sub_100008534 : 100 -> 144
~ sub_100022eb4 -> sub_100022ee0 : 240 -> 276
CStrings:
+ "Parser SetBlock failed with ret=0x%x, pbt=%d, data=%p, block_size=%u, indexes=%p, nindex=%u"
+ "Parser e: failed to set PTUC TLS RR LUT dbv_nits=%d, attempt %u/%u\n"
- "Parser SetBlock failed with 0x%x"
- "Parser e: failed to set PTUC TLS RR LUT brightness %d\n"
```
