## HeartRateCoordinator

> `/System/Library/PrivateFrameworks/HeartRateCoordinator.framework/HeartRateCoordinator`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4a80` | `0x4ad0` | **`+0x50`** |
| `__TEXT.__oslogstring` | `0x48d` | `0x4cf` | **`+0x42`** |
| `__TEXT.__unwind_info` | `0x298` | `0x290` | **`-0x8`** |

### Other Changes

```diff

-40.0.0.0.0
+41.1.0.0.0
CStrings:
+ "sending filtered HR with uuid : %{private}@, bpm : %{sensitive}f, confidence : %f, confidenceLevel : %{sensitive}u, context : %ld, date : %{private}@"
+ "sending one second streaming hr with uuid : %{private}@, bpm : %{sensitive}f, confidence : %f, confidenceLevel : %{sensitive}u, context : %ld, date : %{private}@"
- "sending filtered HR with uuid : %{private}@, bpm : %{sensitive}f, confidence : %f, context : %ld, date : %{private}@"
- "sending one second streaming hr with uuid : %{private}@, bpm : %{sensitive}f, confidence : %f, context : %ld, date : %{private}@"
```
