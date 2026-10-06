## MPSImage

> `/System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSImage.framework/MPSImage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0xc2d00` | `0xc3050` | **`+0x350`** |
| `__TEXT.__text` | `0x4734c` | `0x4754c` | **`+0x200`** |
| `__AUTH_CONST.__const` | `0x43ae0` | `0x43c18` | **`+0x138`** |
| `__TEXT.__cstring` | `0x13ba7` | `0x13c1f` | **`+0x78`** |
| `__AUTH_CONST.__auth_got` | `0x310` | `0x328` | **`+0x18`** |
| `__DATA.__bss` | `0x50` | `0x68` | **`+0x18`** |
| `__DATA.__data` | `—` | `0x1` | **`+0x1`** |

### Other Changes

```diff

-  Functions: 862
-  Symbols:   291
-  CStrings:  2405
+  Functions: 864
+  Symbols:   294
+  CStrings:  2409
Symbols:
+ _atoi
+ _getenv
+ _objc_retain_x28
CStrings:
+ "Encoding SIFT using F32 atomics\n"
+ "Encoding SIFT using fused + multifetch: %s\n"
+ "MPS_SIFT_FLOAT_ATOMICS"
+ "MPS_SIFT_MULTIFETCH"
```
