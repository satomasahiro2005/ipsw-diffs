## libmis.dylib

> `/usr/lib/libmis.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x390` | `0x4e8` | **`+0x158`** |
| `__AUTH.__data` | `0x198` | `0x80` | **`-0x118`** |
| `__DATA.__bss` | `0xc80` | `0xc00` | **`-0x80`** |
| `__DATA_DIRTY.__bss` | `0x1a0` | `0x210` | **`+0x70`** |
| `__DATA.__data` | `0x2f0` | `0x2b8` | **`-0x38`** |
| `__TEXT.__text` | `0x3c71c` | `0x3c6fc` | **`-0x20`** |
| `__DATA.__common` | `0x70` | `0x68` | **`-0x8`** |
| `__DATA_DIRTY.__common` | `0x18` | `0x20` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xe68` | `0xe70` | **`+0x8`** |

### Other Changes

```text
Functions:
~ _decompressECPublicKey : 424 -> 416
~ _CTGetICDPFederationType : 316 -> 288
~ _X509ChainCheckPathWithOptions : 1580 -> 1584
```
