## libauthinstall.dylib

> `/usr/lib/libauthinstall.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb9a08` | `0xb9a54` | **`+0x4c`** |
| `__DATA_CONST.__got` | `0x410` | `0x418` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1155.0.5.0.0
+1155.40.6.0.0

-  Symbols:   4986
+  Symbols:   4987
Symbols:
+ _kAMSupportHttpOptionRequestHTTPAllowed
Functions:
~ _AMAuthInstallApFinalize : 264 -> 288
~ _AMAuthInstallUpdaterPersonalize : 772 -> 796
~ _tss_submit_job_with_retry : 1836 -> 1876
~ _SEUpdaterGetTags : 2212 -> 2200
CStrings:
+ "HelsinkiRestore-58.1.4"
+ "VinylRestore-178~8275"
+ "libauthinstall_device-1155.40.6"
- "HelsinkiRestore-58.0.45"
- "VinylRestore-178~7453"
- "libauthinstall_device-1155.0.5"
```
