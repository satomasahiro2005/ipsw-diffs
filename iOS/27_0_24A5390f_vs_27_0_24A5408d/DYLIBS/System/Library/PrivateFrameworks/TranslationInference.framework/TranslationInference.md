## TranslationInference

> `/System/Library/PrivateFrameworks/TranslationInference.framework/TranslationInference`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7f594` | `0x80ca0` | **`+0x170c`** |
| `__TEXT.__oslogstring` | `0xe4d` | `0xf2d` | **`+0xe0`** |
| `__AUTH_CONST.__const` | `0x2c10` | `0x2c98` | **`+0x88`** |
| `__TEXT.__cstring` | `0x16fe` | `0x175e` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x127d` | `0x12bd` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1228` | `0x1264` | **`+0x3c`** |
| `__TEXT.__swift5_typeref` | `0x1550` | `0x1580` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0xbd8` | `0xbf8` | **`+0x20`** |
| `__TEXT.__const` | `0x3ad8` | `0x3af8` | **`+0x20`** |
| `__TEXT.__eh_frame` | `0x3cc8` | `0x3ca8` | **`-0x20`** |
| `__TEXT.__swift5_capture` | `0x208` | `0x1e8` | **`-0x20`** |
| `__TEXT.__unwind_info` | `0x1788` | `0x17a8` | **`+0x20`** |
| `__DATA.__data` | `0x8c0` | `0x8d8` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x11d0` | `0x11e0` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x294` | `0x290` | **`-0x4`** |

### Other Changes

```diff

-385.0.0.0.0
+388.0.0.0.0

-  Functions: 1734
-  Symbols:   722
-  CStrings:  246
+  Functions: 1747
+  Symbols:   725
+  CStrings:  251
Symbols:
+ _objc_retain_x19
+ _symbolic _____6locale_t 10Foundation6LocaleV
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 16GenerativeModels0eF12AvailabilityV0G0O
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 16GenerativeModels0cD12AvailabilityV0E0O So16os_unfair_lock_sV
- _swift_willThrowTypedImpl
CStrings:
+ "Etiquette file not available for locale: "
+ "GMS initial availability (startup reconcile): useCase=%{public}s, state=%{public}s"
+ "None of the expected assets for this use case are listed in the model bundle (the bundle manifest is likely misconfigured)"
+ "Saudi Arabian Modern Standard Arabic"
+ "embeddings"
```
