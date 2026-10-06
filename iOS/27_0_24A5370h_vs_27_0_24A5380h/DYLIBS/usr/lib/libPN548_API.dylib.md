## libPN548_API.dylib

> `/usr/lib/libPN548_API.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f3c4` | `0x3f97c` | **`+0x5b8`** |
| `__TEXT.__cstring` | `0x91ab` | `0x9261` | **`+0xb6`** |
| `__TEXT.__oslogstring` | `0x7804` | `0x789e` | **`+0x9a`** |
| `__AUTH_CONST.__cfstring` | `0x700` | `0x740` | **`+0x40`** |
| `__TEXT.__const` | `0x600` | `0x640` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x2f8` | `0x2e0` | **`-0x18`** |

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

-  CStrings:  1773
+  CStrings:  1782
CStrings:
+ "%s:%i ---- Core Dump Addr ----"
+ "%s:%i Running build from (B&I) Stockholm_Base-370.38.2"
+ "%s:%i Unknown chip model ID !"
+ "%s:%i cfg=0x%04x addr1=0x%08x len1=0x%04x addr2=0x%08x len2=0x%04x"
+ "%{public}s:%i ---- Core Dump Addr ----"
+ "%{public}s:%i Running build from (B&I) Stockholm_Base-370.38.2"
+ "%{public}s:%i Unknown chip model ID !"
+ "%{public}s:%i cfg=0x%04x addr1=0x%08x len1=0x%04x addr2=0x%08x len2=0x%04x"
+ "Degraded mode"
+ "Unknown Error"
+ "_NFDriverGetSiliconName"
- "%s:%i Running build from (B&I) Stockholm_Base-370.37"
- "%{public}s:%i Running build from (B&I) Stockholm_Base-370.37"
```
