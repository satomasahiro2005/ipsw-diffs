## AudioAnalyticsExternal

> `/System/Library/PrivateFrameworks/AudioAnalyticsExternal.framework/AudioAnalyticsExternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6c170` | `0x6c2cc` | **`+0x15c`** |
| `__AUTH_CONST.__auth_got` | `0x1290` | `0x12a0` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x2b6e` | `0x2b7e` | **`+0x10`** |

### Other Changes

```diff

-295.0.0.0.0
+297.0.0.0.0
Functions:
~ sub_2288eb328 -> sub_22961d328 : 1156 -> 1164
~ sub_2288ecdec -> sub_22961edf4 : 1340 -> 1348
~ sub_2288f723c -> sub_22962924c : 1100 -> 1416
~ sub_2288f9498 -> sub_22962b5e4 : 892 -> 900
~ sub_22894cfe8 -> sub_22967f13c : 712 -> 720
CStrings:
+ "Skipping RTCWorker for reporter configured with AudioServiceTypeUnknown. Events would be dropped in RTCReporting. { reporterID=%lld }"
- "Reporter configured with AudioServiceTypeUnknown. Events will likely be dropped in RTCReporting. { reporterID=%lld }"
```
