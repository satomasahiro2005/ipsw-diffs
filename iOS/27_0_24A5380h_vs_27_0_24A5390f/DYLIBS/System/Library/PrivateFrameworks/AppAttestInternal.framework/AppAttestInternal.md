## AppAttestInternal

> `/System/Library/PrivateFrameworks/AppAttestInternal.framework/AppAttestInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x69b10` | `0x69b78` | **`+0x68`** |
| `__TEXT.__cstring` | `0x64ee` | `0x651e` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x389a` | `0x386a` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x1008` | `0x1030` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0x1078` | `0x1080` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x34` | `0x38` | **`+0x4`** |

### Other Changes

```diff

-153.0.0.0.0
+154.0.0.0.0

-  Functions: 1488
+  Functions: 1489
CStrings:
+ "AppAttest (%@-154) - %@"
- "AppAttest (%@-153) - %@"
```
