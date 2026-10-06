## HealthTopicsDaemonPlugin

> `/System/Library/PrivateFrameworks/HealthTopicsDaemonPlugin.framework/HealthTopicsDaemonPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf880` | `0xfee8` | **`+0x668`** |
| `__AUTH_CONST.__auth_got` | `0x730` | `0x770` | **`+0x40`** |
| `__AUTH_CONST.__objc_const` | `0x848` | `0x868` | **`+0x20`** |
| `__TEXT.__const` | `0x420` | `0x410` | **`-0x10`** |
| `__TEXT.__oslogstring` | `0x5bd` | `0x5cd` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1f5` | `0x205` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1e4` | `0x1f0` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x31e` | `0x328` | **`+0xa`** |
| `__TEXT.__swift5_capture` | `0xf4` | `0xfc` | **`+0x8`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

+  - /System/Library/PrivateFrameworks/HealthUtilities.framework/HealthUtilities

-  Functions: 213
-  Symbols:   341
+  Functions: 214
+  Symbols:   343
Symbols:
+ _objc_retain_x21
+ _swift_retain_x28
+ _symbolic _____ySiG 15Synchronization5MutexVAARi_zrlE
- _objc_retain_x22
CStrings:
+ "PERFTOPIC blocking topic=%{public}s debugID=%{public}s heldMs=%{public}f waitedMs=%{public}f kind=%{public}s"
- "PERFTOPIC blocking topic=%{public}s heldMs=%{public}f waitedMs=%{public}f kind=%{public}s"
```
