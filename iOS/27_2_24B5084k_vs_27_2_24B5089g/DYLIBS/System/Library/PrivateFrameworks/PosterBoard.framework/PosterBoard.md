## PosterBoard

> `/System/Library/PrivateFrameworks/PosterBoard.framework/PosterBoard`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x3bc8` | `0x3a38` | **`-0x190`** |
| `__DATA_DIRTY.__objc_data` | `0x6e98` | `0x7028` | **`+0x190`** |
| `__DATA.__bss` | `0x2f00` | `0x2e20` | **`-0xe0`** |
| `__DATA_DIRTY.__bss` | `0x1520` | `0x1600` | **`+0xe0`** |
| `__TEXT.__text` | `0x277d84` | `0x277d68` | **`-0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x9d40` | `0x9d48` | **`+0x8`** |

### Other Changes

```diff

-355.2.4.0.0
+355.2.6.200.0
Functions:
~ ___54-[PBFPosterSnapshotManager _lock_kickoffNextOperation]_block_invoke.127 : 1696 -> 1676
~ -[PBFPosterSnapshotManager ingestSnapshotCollection:forConfiguration:error:] : 3804 -> 3796
```
