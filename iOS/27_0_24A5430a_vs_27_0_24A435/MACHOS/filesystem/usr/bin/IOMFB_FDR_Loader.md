## IOMFB_FDR_Loader

> `/usr/bin/IOMFB_FDR_Loader`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x2820` | `0x2b40` | **`+0x320`** |
| `__TEXT.__text` | `0x34890` | `0x34b08` | **`+0x278`** |
| `__TEXT.__cstring` | `0x8f1e` | `0x8fa2` | **`+0x84`** |
| `__DATA_CONST.__cfstring` | `0x480` | `0x4a0` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x5e8` | `0x5f0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-  CStrings:  1066
+  CStrings:  1078
CStrings:
+ "  Overriding LLC bin to max (unity LUTs): %.2f, original bin: %.2f\n"
+ "N237b"
+ "N237s"
+ "N238b"
+ "N238s"
+ "N240"
+ "V63"
+ "V64"
+ "V64s"
+ "V68"
+ "soc-revision"
+ "v64s"
```
