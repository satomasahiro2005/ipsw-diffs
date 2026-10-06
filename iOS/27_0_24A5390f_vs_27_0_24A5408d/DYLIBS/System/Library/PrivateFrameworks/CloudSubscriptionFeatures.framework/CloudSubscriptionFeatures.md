## CloudSubscriptionFeatures

> `/System/Library/PrivateFrameworks/CloudSubscriptionFeatures.framework/CloudSubscriptionFeatures`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x112fec` | `0x114c0c` | **`+0x1c20`** |
| `__AUTH_CONST.__const` | `0x9270` | `0x93f0` | **`+0x180`** |
| `__TEXT.__oslogstring` | `0x737d` | `0x749d` | **`+0x120`** |
| `__TEXT.__const` | `0xb764` | `0xb874` | **`+0x110`** |
| `__DATA.__bss` | `0xc540` | `0xc640` | **`+0x100`** |
| `__TEXT.__swift5_reflstr` | `0x25d1` | `0x2641` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x2e10` | `0x2e6c` | **`+0x5c`** |
| `__TEXT.__cstring` | `0x4711` | `0x4751` | **`+0x40`** |
| `__AUTH_CONST.__auth_got` | `0x10e0` | `0x1118` | **`+0x38`** |
| `__TEXT.__constg_swiftt` | `0x2bbc` | `0x2bf4` | **`+0x38`** |
| `__TEXT.__eh_frame` | `0xace0` | `0xaca8` | **`-0x38`** |
| `__TEXT.__swift5_typeref` | `0x2a8c` | `0x2ab4` | **`+0x28`** |
| `__AUTH_CONST.__objc_const` | `0x3588` | `0x35a8` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x550` | `0x570` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x169c` | `0x16bc` | **`+0x20`** |
| `__TEXT.__swift5_proto` | `0x864` | `0x870` | **`+0xc`** |
| `__DATA_DIRTY.__objc_data` | `0xf10` | `0xf18` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x35c` | `0x364` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x87c` | `0x878` | **`-0x4`** |

### Other Changes

```diff

-301.24.0.26.1
+301.24.0.29.0

-  Functions: 4876
-  Symbols:   1802
-  CStrings:  955
+  Functions: 4899
+  Symbols:   1809
+  CStrings:  957
Symbols:
+ ___swift_closure_destructor.104Tm
+ ___swift_closure_destructor.173Tm
+ ___swift_closure_destructor.77Tm
+ ___swift_memcpy144_8
+ _associated conformance 25CloudSubscriptionFeatures20WaitlistDequeueEventV9FeatureIDOSHAASQ
+ _symbolic _____ 25CloudSubscriptionFeatures20WaitlistDequeueEventV
+ _symbolic _____ 25CloudSubscriptionFeatures20WaitlistDequeueEventV9FeatureIDO
+ _symbolic _____Sgyc 10Foundation4DateV
+ _symbolic _____yKc 25CloudSubscriptionFeatures40SignupForWaitlistRequestFinishDiagnosticV
+ _type_layout_string 25CloudSubscriptionFeatures20WaitlistDequeueEventV
- ___swift_closure_destructor.100Tm
- ___swift_closure_destructor.169Tm
- ___swift_closure_destructor.74Tm
CStrings:
+ "%{public}s hadAllAccess: %{bool}d, hasAllAccess: %{bool}d, shouldUnregister: %{bool}d"
+ "%{public}s: There is an account, skipping unregistration"
+ "%{public}s: We do not have access to all waitlist features, skipping unregistration.\n Old features: %s,\n new features: %s"
+ "%{public}s: We transitioned to having access for all waitlist features, proceeding with unregistration."
+ "Unable to get diagnostic for signup for waitlist finish events: %@"
+ "[%{public}s] Gained access to Enhanced Siri and had a ticket with date: %{public}s, took TimeInterval %{public}f to complete."
+ "[%{public}s] Gained access to Enhanced Siri but did not have a ticket with date."
+ "[%{public}s] Network fetch finished for all features"
+ "com.apple.CloudSubscriptionFeatures.waitlist.dequeue"
- "%s: There is an account, skipping unregistration"
- "%s: We did not transition to having access, skipping unregistration.\n Old features: %s,\n new features: %s"
- "%s: We transitioned to having access for adm"
- "%s: We transitioned to having access for afm"
- "%s: We transitioned to having access, proceeding with unregistration."
- "[%{public}s] CFU code deprecated, skipping CFU checks"
- "[%{public}s]network fetch finished for all features"
```
