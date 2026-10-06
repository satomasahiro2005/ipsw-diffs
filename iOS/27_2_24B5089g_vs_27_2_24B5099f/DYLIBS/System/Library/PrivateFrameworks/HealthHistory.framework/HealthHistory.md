## HealthHistory

> `/System/Library/PrivateFrameworks/HealthHistory.framework/HealthHistory`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x70c38` | `0x72620` | **`+0x19e8`** |
| `__DATA.__data` | `0x1100` | `0x12f0` | **`+0x1f0`** |
| `__TEXT.__constg_swiftt` | `0xcb8` | `0xdb4` | **`+0xfc`** |
| `__DATA_DIRTY.__data` | `0x1d8` | `0x2d0` | **`+0xf8`** |
| `__AUTH.__data` | `0xc50` | `0xce0` | **`+0x90`** |
| `__TEXT.__oslogstring` | `0x31c` | `0x39c` | **`+0x80`** |
| `__TEXT.__swift5_reflstr` | `0xc69` | `0xce9` | **`+0x80`** |
| `__TEXT.__const` | `0x4438` | `0x44a8` | **`+0x70`** |
| `__AUTH_CONST.__auth_got` | `0xd38` | `0xda0` | **`+0x68`** |
| `__AUTH_CONST.__objc_const` | `0x7b8` | `0x820` | **`+0x68`** |
| `__TEXT.__swift5_typeref` | `0xb66` | `0xbcc` | **`+0x66`** |
| `__TEXT.__cstring` | `0xded` | `0xe4d` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x15c4` | `0x161c` | **`+0x58`** |
| `__TEXT.__unwind_info` | `0x16c8` | `0x1720` | **`+0x58`** |
| `__AUTH.__objc_data` | `0x118` | `0x168` | **`+0x50`** |
| `__AUTH_CONST.__const` | `0x24b8` | `0x24e0` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x2384` | `0x23ac` | **`+0x28`** |
| `__DATA_CONST.__objc_protolist` | `0x30` | `0x50` | **`+0x20`** |
| `__DATA_CONST.__objc_protorefs` | `0x20` | `0x30` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x138` | `0x130` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x130` | `0x134` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x88` | `0x84` | **`-0x4`** |

### Other Changes

```diff

-7027.1.45.2.4
+7027.1.54.2.3

-  Functions: 2023
-  Symbols:   576
-  CStrings:  118
+  Functions: 2051
+  Symbols:   594
+  CStrings:  122
Symbols:
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_CLASS_$_OS_dispatch_source
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source
+ __OBJC_$_PROTOCOL_REFS_OS_dispatch_source_memorypressure
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source
+ __OBJC_LABEL_PROTOCOL_$_OS_dispatch_source_memorypressure
+ __OBJC_PROTOCOL_$_OS_dispatch_source
+ __OBJC_PROTOCOL_$_OS_dispatch_source_memorypressure
+ ___swift_closure_destructor.48Tm
+ _flat unique So33OS_dispatch_source_memorypressure_p
+ _swift_retain
+ _swift_retain_x22
+ _symbolic Say_____G 13HealthHistory32UniversalClassificationRuleStoreC6Waiter33_029C022D0631F77B8E28C9465C7DF944LLV
+ _symbolic ScCyyt_____G s5NeverO
+ _symbolic ShySSG
+ _symbolic _____ 13HealthHistory32UniversalClassificationRuleStoreC6Waiter33_029C022D0631F77B8E28C9465C7DF944LLV
+ _symbolic _____Sg s15ContinuousClockV7InstantV
+ _symbolic ______pSg So33OS_dispatch_source_memorypressureP
+ _symbolic ytSgIeAgHr_
- _symbolic _____ s8DurationV
CStrings:
+ "UniversalClassificationRuleStore dropping rules for %{public}ld measures: %{public}s"
+ "UniversalClassificationRuleStore warm did not cover %{public}ld measure(s)"
+ "UniversalClassificationRuleStore.warmAllRules cached rules for %{public}ld measures"
+ "UniversalClassificationRuleStore.warmAllRules failed after caching %{public}ld measures with error: %{public}@"
+ "critical memory pressure"
+ "ontology content replaced"
+ "rulesWarmed(for:)"
- "UniversalClassificationRuleStore.evictCache dropping rules for %ld measures"
- "UniversalClassificationRuleStore.warmAllRules cached rules for %ld measures"
- "UniversalClassificationRuleStore.warmAllRules failed after caching %ld measures with error: %@"
```
