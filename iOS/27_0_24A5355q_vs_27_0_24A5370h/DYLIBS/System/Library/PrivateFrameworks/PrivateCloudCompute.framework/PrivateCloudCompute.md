## PrivateCloudCompute

> `/System/Library/PrivateFrameworks/PrivateCloudCompute.framework/PrivateCloudCompute`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbf178` | `0xbf758` | **`+0x5e0`** |
| `__TEXT.__oslogstring` | `0xc7b` | `0xcdb` | **`+0x60`** |
| `__TEXT.__cstring` | `0x2b1f` | `0x2acf` | **`-0x50`** |
| `__TEXT.__const` | `0xee7c` | `0xeebc` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x83b8` | `0x8388` | **`-0x30`** |
| `__TEXT.__eh_frame` | `0x8168` | `0x8198` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x3c60` | `0x3c48` | **`-0x18`** |
| `__AUTH_CONST.__auth_got` | `0xd20` | `0xd30` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3ef8` | `0x3f04` | **`+0xc`** |
| `__DATA_CONST.__got` | `0x448` | `0x450` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x324` | `0x328` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x370` | `0x374` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-2562.0.0.0.0
+2570.0.5.0.0

-  Functions: 4846
+  Functions: 4845
CStrings:
+ "%s knownRateLimits, bundleIdentifier=%s, featureIdentifier=%s"
+ "boundedNetworkReads2"
+ "close, runningRequests=%s"
+ "knownRateLimits(bundleIdentifier:featureIdentifier:)"
+ "non-progress continuation found while finishProgressReading, xpcRequestID=%ld, continuation=%s"
- "%s knownRateLimits, bundleIdentifier=%s, featureIdentifier=%s, skipFetch=%{bool}d"
- "antiTargetabilityMaxPrefetchedAttestations"
- "boundedNetworkReads"
- "knownRateLimits(bundleIdentifier:featureIdentifier:skipFetch:)"
- "rateLimitRequestMinimumSpacing"
```
