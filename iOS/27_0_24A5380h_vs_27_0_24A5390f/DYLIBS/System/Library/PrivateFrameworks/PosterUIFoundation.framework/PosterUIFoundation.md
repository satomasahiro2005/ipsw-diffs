## PosterUIFoundation

> `/System/Library/PrivateFrameworks/PosterUIFoundation.framework/PosterUIFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94324` | `0x93db0` | **`-0x574`** |
| `__TEXT.__oslogstring` | `0x3961` | `0x38a1` | **`-0xc0`** |
| `__AUTH_CONST.__objc_const` | `0x1efc0` | `0x1ef80` | **`-0x40`** |
| `__TEXT.__cstring` | `0x66a3` | `0x6663` | **`-0x40`** |
| `__TEXT.__objc_methlist` | `0xab8c` | `0xab64` | **`-0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x58e8` | `0x58c8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x29f0` | `0x29d0` | **`-0x20`** |
| `__TEXT.__const` | `0xdc4` | `0xdb4` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1098` | `0x1090` | **`-0x8`** |
| `__DATA.__objc_ivar` | `0xbe4` | `0xbdc` | **`-0x8`** |
| `__DATA_CONST.__got` | `0xf98` | `0xf90` | **`-0x8`** |

### Other Changes

```diff

-347.102.0.0.0
+350.1.100.0.0

-  Functions: 4142
-  Symbols:   7403
-  CStrings:  1493
+  Functions: 4136
+  Symbols:   7395
+  CStrings:  1489
Symbols:
- -[PUIPosterSnapshotter _lock_retryStartupLater]
- -[PUIPosterSnapshotter consecutiveStartupFailuresForTesting]
- -[PUIPosterSnapshotter setConsecutiveStartupFailuresForTesting:]
- _OBJC_IVAR_$_PUIPosterSnapshotter._lock_consecutiveStartupFailures
- _OBJC_IVAR_$_PUIPosterSnapshotter._lock_waitingForRetry
- ___47-[PUIPosterSnapshotter _lock_retryStartupLater]_block_invoke
- _exp2
- _kPFErrorDomain
CStrings:
+ "(%{public}@) Booted extension process is invalid (no error) — treating as a boot failure"
+ "(%{public}@) couldn't get assertions; invalidating so the request can be retried on a fresh process"
+ "Snapshotter state error: shouldn't call %s while waiting for extension"
+ "\xb1"
- "(%{public}@) Booted extension process is invalid (no error) — treating as a startup failure"
- "(%{public}@) Exceeded %lu consecutive mid-snapshot interruptions, giving up"
- "(%{public}@) Exceeded %lu consecutive startup failures, giving up"
- "(%{public}@) Retrying startup in %.1f seconds (attempt %lu/%lu)"
- "(%{public}@) couldn't get assertions, deferring snapshot"
- "-[PUIPosterSnapshotter setConsecutiveStartupFailuresForTesting:]"
- "Snapshotter state error: shouldn't call %s while waiting: for retry? %d; for extension? %d"
- "\xc1"
```
