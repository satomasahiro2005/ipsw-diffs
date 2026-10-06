## DaemonUtils

> `/System/Library/Frameworks/LocalAuthentication.framework/Support/DaemonUtils.framework/DaemonUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x8d64` | `0x8dbc` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x9d3` | `0xa0b` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x2b20` | `0x2b00` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0x1278` | `0x1258` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xb00` | `0xaf0` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x2c0` | `0x2b8` | **`-0x8`** |
| `__TEXT.__const` | `0x168` | `0x160` | **`-0x8`** |
| `__TEXT.__cstring` | `0x597` | `0x595` | **`-0x2`** |

### Other Changes

```diff

-2305.0.0.0.1
+2319.0.16.502.1

-  Functions: 350
-  Symbols:   754
+  Functions: 347
+  Symbols:   750
Symbols:
+ -[LAAnalyticsDTO initForStatusMonitoringWithEnvironment:device:workQueue:]
+ _OBJC_IVAR_$_LAAnalyticsDTO._device
+ ___74-[LAAnalyticsDTO initForStatusMonitoringWithEnvironment:device:workQueue:]_block_invoke
- -[Caller asid]
- -[Caller processId]
- -[Caller userId]
- -[LAAnalyticsDTO initForStatusMonitoringWithEnvironment:workQueue:]
- _OBJC_IVAR_$_Caller._asid
- ___67-[LAAnalyticsDTO initForStatusMonitoringWithEnvironment:workQueue:]_block_invoke
- _audit_token_to_pid
CStrings:
+ "Skipping status check (%{public}@): setup=%d, unlock=%d"
- "a"
```
