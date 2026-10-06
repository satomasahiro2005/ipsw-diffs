## MediaServices

> `/System/Library/PrivateFrameworks/MediaServices.framework/MediaServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59e3c` | `0x5a444` | **`+0x608`** |
| `__TEXT.__oslogstring` | `0x2c42` | `0x2dc7` | **`+0x185`** |
| `__AUTH_CONST.__cfstring` | `0x5a40` | `0x5a60` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6050` | `0x606a` | **`+0x1a`** |
| `__TEXT.__unwind_info` | `0x16f8` | `0x1710` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2fb8` | `0x2fc0` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x5784` | `0x578c` | **`+0x8`** |

### Other Changes

```diff

-4026.100.70.0.0
+4026.110.1.0.0

-  Functions: 2118
-  Symbols:   4446
-  CStrings:  1120
+  Functions: 2122
+  Symbols:   4450
+  CStrings:  1126
Symbols:
+ -[MSVSonicAssertionObserver assertionWillInvalidate:]
+ GCC_except_table2055
+ GCC_except_table2071
+ GCC_except_table2073
+ GCC_except_table2074
+ __MSVSonicPerformRenewalLocked
+ __MSVSonicScheduleRenewalLocked
+ ____MSVSonicScheduleRenewalLocked_block_invoke
- GCC_except_table2051
- GCC_except_table2066
- GCC_except_table2067
- GCC_except_table2069
CStrings:
+ "MSVSonicAssertion-renewal"
+ "[MSVSonicAssertion] Failed to renew RBSAssertion %p error=%{public}@"
+ "[MSVSonicAssertion] Invalidating RBSAssertion %p"
+ "[MSVSonicAssertion] Invalidating RBSAssertion %p [proactive age-out, unused]"
+ "[MSVSonicAssertion] Proactive renewal timer fired [still in use] assertion=%p"
+ "[MSVSonicAssertion] RBSAssertion %p received expiration warning from RunningBoard"
+ "[MSVSonicAssertion] Renewed RBSAssertion %p -> %p [proactive renewal before expiration]"
+ "[MSVSonicAssertion] Scheduling RBSAssertion %p Invalidation"
- "[MSVSonicAssertion] Invalidating RBSAssertion %p] Timeout"
- "[MSVSonicAssertion] Releasing os_transaction %p Timeout"
```
