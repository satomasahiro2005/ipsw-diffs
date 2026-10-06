## PrivateCloudCompute

> `/System/Library/PrivateFrameworks/PrivateCloudCompute.framework/PrivateCloudCompute`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbfff4` | `0xc08e0` | **`+0x8ec`** |
| `__TEXT.__unwind_info` | `0x3c60` | `0x3dc0` | **`+0x160`** |
| `__TEXT.__swift5_reflstr` | `0x3da6` | `0x3e06` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2b6f` | `0x2bbf` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x3fc0` | `0x3ffc` | **`+0x3c`** |
| `__TEXT.__const` | `0xef1c` | `0xef4c` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0xcdb` | `0xcab` | **`-0x30`** |
| `__AUTH_CONST.__auth_got` | `0xd30` | `0xd28` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x448` | `0x440` | **`-0x8`** |

### Other Changes

```diff

-2570.0.25.502.2
+2570.2.1.0.0

-  Functions: 4840
+  Functions: 4846

-  CStrings:  368
+  CStrings:  370
CStrings:
+ "XPCWrapper closing file="
+ "clientTimeout"
+ "missingTrailingMetadata"
+ "will fail running continuation, error=%@, xpcRequestID=%ld, continuation=%s"
- "close, runningRequests=%s"
- "non-progress continuation found while finishProgressReading, xpcRequestID=%ld, continuation=%s"
```
