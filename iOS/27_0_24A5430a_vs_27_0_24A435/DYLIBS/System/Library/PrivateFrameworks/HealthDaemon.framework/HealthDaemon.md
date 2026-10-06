## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/HealthDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x96c524` | `0x96cc38` | **`+0x714`** |
| `__AUTH_CONST.__objc_const` | `0x83a28` | `0x83bc8` | **`+0x1a0`** |
| `__TEXT.__objc_methlist` | `0x466c4` | `0x46784` | **`+0xc0`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b4a8` | `0x1b530` | **`+0x88`** |
| `__TEXT.__const` | `0x26c00` | `0x26c50` | **`+0x50`** |
| `__TEXT.__cstring` | `0x85417` | `0x85458` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x40860` | `0x408a0` | **`+0x40`** |
| `__DATA.__objc_ivar` | `0x4594` | `0x45b4` | **`+0x20`** |
| `__DATA.__bss` | `0x8d90` | `0x8da0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x3de8` | `0x3df0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x5cf8` | `0x5d00` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x21780` | `0x21788` | **`+0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0xe5c` | `0xe60` | **`+0x4`** |

### Other Changes

```diff

-  Functions: 41522
-  Symbols:   60189
-  CStrings:  14361
+  Functions: 41538
+  Symbols:   60215
+  CStrings:  14363
Symbols:
+ -[HDDemoDataPerson heartRateVariabilityRMSSDSampleFrequencyStdDev]
+ -[HDDemoDataPerson heartRateVariabilityRMSSDSampleFrequency]
+ -[HDDemoDataPerson heartRateVariabilityRMSSD]
+ -[HDDemoDataPerson hrvSpreadDaySigma]
+ -[HDDemoDataPerson hrvSpreadNightSigma]
+ -[HDDemoDataPerson hrvWakeBurstCenter]
+ -[HDDemoDataPerson hrvWakeBurstSigma]
+ -[HDDemoDataPerson hrvWakeBurstWidth]
+ -[HDDemoDataPerson setHeartRateVariabilityRMSSD:]
+ -[HDDemoDataPerson setHeartRateVariabilityRMSSDSampleFrequency:]
+ -[HDDemoDataPerson setHeartRateVariabilityRMSSDSampleFrequencyStdDev:]
+ -[HDDemoDataPerson setHrvSpreadDaySigma:]
+ -[HDDemoDataPerson setHrvSpreadNightSigma:]
+ -[HDDemoDataPerson setHrvWakeBurstCenter:]
+ -[HDDemoDataPerson setHrvWakeBurstSigma:]
+ -[HDDemoDataPerson setHrvWakeBurstWidth:]
+ _HKQuantityTypeIdentifierHeartRateVariabilityRMSSD
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilityRMSSD
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilityRMSSDSampleFrequency
+ _OBJC_IVAR_$_HDDemoDataPerson._heartRateVariabilityRMSSDSampleFrequencyStdDev
+ _OBJC_IVAR_$_HDDemoDataPerson._hrvSpreadDaySigma
+ _OBJC_IVAR_$_HDDemoDataPerson._hrvSpreadNightSigma
+ _OBJC_IVAR_$_HDDemoDataPerson._hrvWakeBurstCenter
+ _OBJC_IVAR_$_HDDemoDataPerson._hrvWakeBurstSigma
+ _OBJC_IVAR_$_HDDemoDataPerson._hrvWakeBurstWidth
+ _exp
CStrings:
+ "HDDemoDataHeartSampleGeneratorNextHRVRMSSDSampleTimeKey"
+ "Watch8,1"
```
