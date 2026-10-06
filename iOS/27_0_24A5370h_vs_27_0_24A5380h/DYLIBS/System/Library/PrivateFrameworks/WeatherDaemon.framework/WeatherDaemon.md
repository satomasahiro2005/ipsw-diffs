## WeatherDaemon

> `/System/Library/PrivateFrameworks/WeatherDaemon.framework/WeatherDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__data` | `0x7588` | `0x8170` | **`+0xbe8`** |
| `__AUTH.__data` | `0x1560` | `0x9c0` | **`-0xba0`** |
| `__AUTH.__objc_data` | `0x330` | `0xd8` | **`-0x258`** |
| `__DATA_DIRTY.__objc_data` | `0x8d8` | `0xb30` | **`+0x258`** |
| `__TEXT.__text` | `0x24162c` | `0x2414cc` | **`-0x160`** |
| `__TEXT.__eh_frame` | `0x10230` | `0x10178` | **`-0xb8`** |
| `__DATA.__data` | `0x3248` | `0x31c0` | **`-0x88`** |
| `__TEXT.__unwind_info` | `0x91a0` | `0x9138` | **`-0x68`** |
| `__TEXT.__swift_as_cont` | `0x678` | `0x638` | **`-0x40`** |
| `__DATA.__common` | `0x120` | `0x100` | **`-0x20`** |
| `__DATA_DIRTY.__common` | `0x170` | `0x190` | **`+0x20`** |
| `__TEXT.__const` | `0x1af18` | `0x1aef8` | **`-0x20`** |
| `__TEXT.__swift5_typeref` | `0x5fb2` | `0x5fa6` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0x3158` | `0x3160` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x1148` | `0x1140` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__oslogstring`

### Other Changes

```diff

-1435.0.0.0.0
+1439.0.0.0.0

-  Functions: 15332
-  Symbols:   3970
+  Functions: 15320
+  Symbols:   3964
Symbols:
- _OUTLINED_FUNCTION_984
- _OUTLINED_FUNCTION_985
- _get_type_metadata 15Synchronization5MutexVy13WeatherDaemon0C16DataSentinelFileC16ObservationState33_5084CA2EB35E227A781A2AFFEB9A96ACLLOG noncopyable
- _get_type_metadata 15Synchronization5MutexVy13WeatherDaemon0C5ClockC5State33_32F46C13626033132CABF29FBF26091CLLOG noncopyable
- _swift_runtimeSupportsNoncopyableTypes
- _swift_willThrowTypedImpl
CStrings:
+ "Data exceeds maximum age, returning nil; model=%{public}s, modified=%{public}@, now=%{public}@"
+ "Data has expired, returning nil; model=%{public}s, expiration=%{public}@, now=%{public}@"
- "Data exceeds maximum age, returning nil; model=%{public}s, modified=%{public}s, now=%{public}s"
- "Data has expired, returning nil; model=%{public}s, expiration=%{public}s, now=%{public}s"
```
