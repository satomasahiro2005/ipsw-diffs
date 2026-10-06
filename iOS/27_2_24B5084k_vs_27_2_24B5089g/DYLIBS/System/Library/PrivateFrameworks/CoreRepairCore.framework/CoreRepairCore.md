## CoreRepairCore

> `/System/Library/PrivateFrameworks/CoreRepairCore.framework/CoreRepairCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9acbc` | `0x9af5c` | **`+0x2a0`** |
| `__TEXT.__oslogstring` | `0xa541` | `0xa5ad` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x7e81` | `0x7ed4` | **`+0x53`** |
| `__TEXT.__objc_methlist` | `0x4f6c` | `0x4f94` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x9560` | `0x9580` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2908` | `0x2928` | **`+0x20`** |
| `__TEXT.__const` | `0x860` | `0x880` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1658` | `0x1668` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6f0` | `0x6f8` | **`+0x8`** |

### Other Changes

```diff

-1307.40.46.0.0
+1307.40.51.0.0

-  Functions: 2788
-  Symbols:   699
-  CStrings:  2634
+  Functions: 2792
+  Symbols:   703
+  CStrings:  2637
Symbols:
+ _NSURLErrorDomain
+ _kCRNetworkRetryDelaySeconds
+ _kCRNetworkRetryMaxAttempts
+ _kCRNetworkRetryWindowSeconds
CStrings:
+ "+[CRUtils shouldRetryNetworkError:attempt:startedAtClock:]"
+ "[%s] retry window closed after %{public}.0fs (attempt %{public}lu/%{public}lu); failing instead of retrying"
+ "kCFErrorDomainCFNetwork"
```
