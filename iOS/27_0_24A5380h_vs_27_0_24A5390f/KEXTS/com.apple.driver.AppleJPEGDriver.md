## com.apple.driver.AppleJPEGDriver

> `com.apple.driver.AppleJPEGDriver`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x2b598` | `0x2d24c` | **`+0x1cb4`** |
| `__DATA.__data` | `0x2208` | `0x2e58` | **`+0xc50`** |
| `__TEXT.__const` | `0x39ec` | `0x3e9c` | **`+0x4b0`** |
| `__TEXT.__os_log` | `0x9690` | `0x9b22` | **`+0x492`** |
| `__DATA_CONST.__const` | `0x4b50` | `0x4df0` | **`+0x2a0`** |
| `__TEXT.__cstring` | `0x2a63` | `0x2b2e` | **`+0xcb`** |
| `__DATA_CONST.__kalloc_type` | `0xd80` | `0xdc0` | **`+0x40`** |
| `__DATA.__common` | `0x3d0` | `0x3f8` | **`+0x28`** |
| `__DATA_CONST.__mod_init_func` | `0xc0` | `0xc8` | **`+0x8`** |
| `__DATA_CONST.__mod_term_func` | `0xc0` | `0xc8` | **`+0x8`** |

### Other Changes

```diff

-8.1.3.0.0
-  Functions: 1741
+8.1.5.0.0
+  Functions: 1807

-  CStrings:  520
+  CStrings:  533
CStrings:
+ "1211111212221212121111111222112222122222211111"
+ "121121"
+ "AppleJPEGDriver: %s : mHal unexpectedly NULL\n"
+ "AppleJPEGDriver: %s(): Fastsim detected via platform fuses\n"
+ "AppleJPEGDriver: %s: failed to create fuse descriptor at 0x%llx\n"
+ "AppleJPEGDriver: %s: failed to map fuse descriptor at 0x%llx\n"
+ "AppleJPEGDriver: %s: pre-silicon platform (PV_RUNTIME_ENV=0x%x, JPEG_PRESENT=0x%x), fastsim=%d\n"
+ "AppleJPEGDriver: ** %s : dim out of range pixelsX=%u pixelsY=%u decW=%u decH=%u cropW=%u cropH=%u cropOffX=%u cropOffY=%u\n"
+ "AppleJPEGDriver: ** %s : xOffset %u / yOffset %u / pixelsX %u / pixelsY %u out of range\n"
+ "AppleJPEGDriver: jpeg_huffman_set() - Invalid input\n"
+ "StockFunctions"
+ "bool AppleJPEGWrapperControl::getIsFsim() const"
+ "site.StockFunctions"
+ "virtual bool NerineFunctions::detectFastsim()"
+ "virtual bool StockFunctions::setupAXIRegisterOffset(uint32_t, uint64_t)"
- "121111121222121212111111122112222122222211111"
- "12112"
```
