## appleaccountd

> `/usr/libexec/appleaccountd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f2e74` | `0x3f7494` | **`+0x4620`** |
| `__TEXT.__oslogstring` | `0x20ccd` | `0x210ad` | **`+0x3e0`** |
| `__DATA.__bss` | `0x13980` | `0x13800` | **`-0x180`** |
| `__DATA.__data` | `0x14300` | `0x14480` | **`+0x180`** |
| `__TEXT.__eh_frame` | `0x146cc` | `0x14824` | **`+0x158`** |
| `__DATA_CONST.__const` | `0x13f60` | `0x14048` | **`+0xe8`** |
| `__TEXT.__objc_methname` | `0x77d5` | `0x78b5` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x65fc` | `0x66a0` | **`+0xa4`** |
| `__TEXT.__objc_stubs` | `0x4d40` | `0x4de0` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0xc5f4` | `0xc680` | **`+0x8c`** |
| `__DATA.__objc_const` | `0x1e0f0` | `0x1e170` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x8510` | `0x8588` | **`+0x78`** |
| `__TEXT.__swift5_fieldmd` | `0x6638` | `0x66a0` | **`+0x68`** |
| `__TEXT.__const` | `0x13350` | `0x133b0` | **`+0x60`** |
| `__TEXT.__swift5_typeref` | `0x7993` | `0x79eb` | **`+0x58`** |
| `__TEXT.__auth_stubs` | `0x37d0` | `0x3810` | **`+0x40`** |
| `__DATA.__common` | `0x4b8` | `0x4e0` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0x1720` | `0x1748` | **`+0x28`** |
| `__DATA_CONST.__auth_ptr` | `0x1678` | `0x16a0` | **`+0x28`** |
| `__DATA_CONST.__auth_got` | `0x1bf0` | `0x1c10` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x2024` | `0x2044` | **`+0x20`** |
| `__TEXT.__swift5_assocty` | `0x950` | `0x938` | **`-0x18`** |
| `__TEXT.__swift_as_cont` | `0x11c4` | `0x11d8` | **`+0x14`** |
| `__TEXT.__swift_as_ret` | `0x87c` | `0x88c` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0xc74` | `0xc68` | **`-0xc`** |
| `__TEXT.__swift_as_entry` | `0x674` | `0x680` | **`+0xc`** |
| `__TEXT.__swift5_types` | `0x638` | `0x63c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_stublist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__cstring`
- `__TEXT.__objc_classname`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-1067.0.0.0.0
+1069.125.4.0.0

+  - /usr/lib/libbsm.0.dylib

-  Functions: 10245
-  Symbols:   1815
-  CStrings:  4184
+  Functions: 10281
+  Symbols:   1820
+  CStrings:  4205
Symbols:
+ _$s14XPCDistributed9XPCSystemC7SessionC15RemoteInterfaceV10auditTokenSo0F8_token_taSgvg
+ _$s20IntelligencePlatform19PersonEntityTagTypeOMn
+ _SecTaskCopySigningIdentifier
+ _SecTaskCreateWithAuditToken
+ _objc_retain_x1
CStrings:
+ "%s - AutoHeal: CRK not exists on OT, But, Recovery Info Record has an RKC. canRepairUntrustedCRK gate is off. Aborting repair."
+ "%s - AutoHeal: CRK not exists on OT, Recovery Info Record has an RKC, but canRepairCustodian config read failed: %@. Emitting crkRepairNotAllowed with underlying error."
+ "%s - Could not ask CoreCDP to retire a stale PDP repair CFU: %s"
+ "Failed to resolve client bundle ID: could not create SecTask from audit token"
+ "Failed to resolve client bundle ID: could not read signing identifier from audit token"
+ "Failed to resolve client bundle ID: no remote invocation origin for the current XPC call"
+ "Failed to resolve client bundle ID: remote invocation origin has no audit token"
+ "RC upsell eligibility - reporting failure: cohort=%@, errorCode=%ld"
+ "Repair-eligibility config read from URL bag failed: %@. Continuing to TTR."
+ "UrlBagProvider - %s has unexpected type %s; treating as URL-bag anomaly."
+ "UrlBagProvider - canRepairCustodianV2 absent from urlbag; defaulting to false."
+ "UrlBagProvider - canRepairCustodianV2 has unexpected type %s; defaulting to false."
+ "UrlBagProvider - failed to read %s from URL bag: %@."
+ "_TtC13appleaccountd17MegadomeSuggester"
+ "canRepairCustodianV2"
+ "configurationValueForKey:fromCache:completion:"
+ "defaults"
+ "initWithDouble:"
+ "initWithHandle:contact:source:"
+ "isSyncAction"
+ "policy"
+ "process(_:originalStatus:postCFU:telemetryFlowID:flow:isSyncAction:)"
+ "retirementTimeout"
+ "setClientBundleID:"
+ "setIntelligenceScore:"
+ "v24@?0@8@\"NSError\"16"
+ "validateReachability"
+ "🔔 Internal build: %s override is set to: %s"
- "%s - AutoHeal: CRK not exists on OT, But, Recovery Info Record has an RKC. decoupleCRK is not enabled. Aborting repair."
- "RC upsell eligibility - reporting failure: cohort=%@, errorCode=%ld (%s)"
- "Using Health Check interval - One Week"
- "_TtC13appleaccountd26CustodianMegadomeSuggester"
- "canRepairCustodian"
- "com.apple.appleaccount.rcUpsellEligibility"
- "process(_:originalStatus:postCFU:telemetryFlowID:flow:)"
```
