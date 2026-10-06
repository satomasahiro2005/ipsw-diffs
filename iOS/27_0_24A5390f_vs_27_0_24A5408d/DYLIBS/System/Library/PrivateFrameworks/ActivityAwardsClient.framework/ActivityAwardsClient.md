## ActivityAwardsClient

> `/System/Library/PrivateFrameworks/ActivityAwardsClient.framework/ActivityAwardsClient`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x55bc` | `0x56d0` | **`+0x114`** |
| `__TEXT.__oslogstring` | `0x839` | `0x8e0` | **`+0xa7`** |
| `__AUTH_CONST.__cfstring` | `0x100` | `0x140` | **`+0x40`** |
| `__TEXT.__cstring` | `0x16c` | `0x173` | **`+0x7`** |

### Other Changes

```diff

-2027.0.21.0.0
+2027.0.22.0.0

-  Functions: 131
+  Functions: 133

-  CStrings:  45
+  CStrings:  49
CStrings:
+ "Calling sendSynchronousRequest from client for initialHistoricalRunStatusWithError"
+ "Got %@ for isInitialHistoricalRunCompleteWithError"
+ "NO"
+ "Unexpectedly got XPC Error for AACTransportItemIsInitialHistoricalRunComplete: %@"
+ "YES"
- "Calling sendSynchronousRequest from client for v"
```
