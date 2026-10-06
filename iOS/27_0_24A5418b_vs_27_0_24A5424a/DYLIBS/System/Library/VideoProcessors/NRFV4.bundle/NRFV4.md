## NRFV4

> `/System/Library/VideoProcessors/NRFV4.bundle/NRFV4`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x25b7b4` | `0x25b84c` | **`+0x98`** |
| `__TEXT.__unwind_info` | `0x5128` | `0x5130` | **`+0x8`** |

### Other Changes

```diff

-764.22.12.0.0
+764.22.13.0.0
Symbols:
+ -[H13FastBayerProcConfig(HR) determineHRConfigFromInputFrame:bounds:usesSyntheticThumbnail:hrConfig:awbComputedGains:]
+ -[H13FastBayerProcConfig(HR) getHRConfigForInputFrame:bounds:usesSyntheticThumbnail:awbComputedGains:lscConfig:hrConfig:outputMetadata:]
- -[H13FastBayerProcConfig(HR) determineHRConfigFromInputFrame:bounds:hrConfig:awbComputedGains:]
- -[H13FastBayerProcConfig(HR) getHRConfigForInputFrame:bounds:awbComputedGains:lscConfig:hrConfig:outputMetadata:]
```
