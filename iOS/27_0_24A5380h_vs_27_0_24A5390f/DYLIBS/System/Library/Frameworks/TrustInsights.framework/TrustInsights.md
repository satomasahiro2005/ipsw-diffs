## TrustInsights

> `/System/Library/Frameworks/TrustInsights.framework/TrustInsights`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1972c` | `0x1a870` | **`+0x1144`** |
| `__TEXT.__oslogstring` | `0x2eb` | `0x42f` | **`+0x144`** |
| `__TEXT.__cstring` | `0x721` | `0x861` | **`+0x140`** |
| `__TEXT.__swift5_reflstr` | `0x43b` | `0x4cb` | **`+0x90`** |
| `__AUTH_CONST.__const` | `0xef8` | `0xf70` | **`+0x78`** |
| `__TEXT.__const` | `0x1d94` | `0x1e04` | **`+0x70`** |
| `__TEXT.__swift5_fieldmd` | `0x620` | `0x67c` | **`+0x5c`** |
| `__AUTH_CONST.__auth_got` | `0x740` | `0x788` | **`+0x48`** |
| `__TEXT.__constg_swiftt` | `0x680` | `0x6b8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x70e` | `0x742` | **`+0x34`** |
| `__TEXT.__swift5_capture` | `0x78` | `0xa0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x60` | `0x70` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x698` | `0x6a8` | **`+0x10`** |

### Other Changes

```diff

-27.0.49.0.0
+27.0.52.0.0

-  Functions: 564
-  Symbols:   352
-  CStrings:  62
+  Functions: 570
+  Symbols:   363
+  CStrings:  74
Symbols:
+ ___swift__destructor
+ ___swift_destroy_boxed_opaque_existential_0
+ _objc_retain
+ _objc_retain_x20
+ _swift_beginAccess
+ _swift_release_x25
+ _swift_retain_x19
+ _symbolic SDySSSo8NSObjectCG
+ _symbolic So14LSBundleRecordC
+ _symbolic _____ 13TrustInsights18EntitlementCheckerV
+ _symbolic _____ 13TrustInsights18EntitlementCheckerV11ApiEndpointO
CStrings:
+ "Call to %{public}s"
+ "Call to %{public}s | operationCategory: %{public}s | requestID: %{public}s | requestedInsight: %{public}s"
+ "Call to %{public}s | status: %{public}s | insightIDsUsed: %{public}s"
+ "Could not validate the app bundle record for the \"com.apple.developer.trustinsights.base\" entitlement"
+ "Initializing InsightEvaluator"
+ "Sending CoreAnalytics event for entitlementChecked: %s"
+ "authorizationStatus(for:)"
+ "com.apple.TrustInsights.entitlementChecked"
+ "com.apple.odi.trustinsights"
+ "reportConsumption(_:insightIDsUsed:)"
+ "requestAuthorization(for:)"
+ "requestEvaluation(context:)"
```
