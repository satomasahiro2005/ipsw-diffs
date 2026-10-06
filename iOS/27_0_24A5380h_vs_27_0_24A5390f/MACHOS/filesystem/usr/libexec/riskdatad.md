## riskdatad

> `/usr/libexec/riskdatad`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4385c` | `0x481ac` | **`+0x4950`** |
| `__TEXT.__eh_frame` | `0x3578` | `0x37a8` | **`+0x230`** |
| `__DATA.__data` | `0x12b0` | `0x1468` | **`+0x1b8`** |
| `__TEXT.__cstring` | `0x990` | `0xb40` | **`+0x1b0`** |
| `__DATA_CONST.__const` | `0x12d8` | `0x1468` | **`+0x190`** |
| `__DATA.__objc_const` | `0xa38` | `0xba8` | **`+0x170`** |
| `__TEXT.__const` | `0x2598` | `0x26a8` | **`+0x110`** |
| `__TEXT.__unwind_info` | `0x10a0` | `0x1180` | **`+0xe0`** |
| `__TEXT.__swift5_capture` | `0x648` | `0x714` | **`+0xcc`** |
| `__TEXT.__constg_swiftt` | `0x6c0` | `0x768` | **`+0xa8`** |
| `__TEXT.__swift5_reflstr` | `0x49b` | `0x53b` | **`+0xa0`** |
| `__DATA.__bss` | `0x2100` | `0x2180` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x7a1` | `0x821` | **`+0x80`** |
| `__TEXT.__swift5_fieldmd` | `0x504` | `0x580` | **`+0x7c`** |
| `__TEXT.__swift5_typeref` | `0xb04` | `0xb6e` | **`+0x6a`** |
| `__TEXT.__auth_stubs` | `0x1df0` | `0x1e50` | **`+0x60`** |
| `__DATA.__objc_data` | `0x280` | `0x2d0` | **`+0x50`** |
| `__DATA_CONST.__auth_got` | `0xf00` | `0xf30` | **`+0x30`** |
| `__TEXT.__swift_as_cont` | `0x380` | `0x3a8` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x208` | `0x228` | **`+0x20`** |
| `__TEXT.__swift_as_entry` | `0x184` | `0x194` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x1b0` | `0x1c0` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x4e0` | `0x4e8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x648` | `0x650` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x40` | `0x48` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x35e` | `0x35a` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x10c` | `0x110` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x5c` | `0x60` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_protos`

### Other Changes

```diff

-27.0.49.0.0
+27.0.52.0.0

-  Functions: 1019
-  Symbols:   823
-  CStrings:  234
+  Functions: 1078
+  Symbols:   830
+  CStrings:  251
Symbols:
+ _$s17CoreODIEssentials0A9ODIConfigV13trustInsightsAC05TrustE13ConfigurationVvg
+ _$s17CoreODIEssentials0A9ODIConfigV26TrustInsightsConfigurationV12globalLimitsSDySdSiGyF
+ _$s17CoreODIEssentials0A9ODIConfigV26TrustInsightsConfigurationV12perAppLimitsSDySdSiGyF
+ _$s17CoreODIEssentials0A9ODIConfigV26TrustInsightsConfigurationV17perBundleIdLimitsSDySSSDySdSiGGyF
+ _$s17CoreODIEssentials0A9ODIConfigV26TrustInsightsConfigurationVMa
+ _$s17CoreODIEssentials23ODIiCloudAccountManagerCAA012ConfigurableE21RequestHeaderProviderAAWP
+ _$s17CoreODIEssentials25TrustInsightsServerClientV9isSandbox3mid14conversationId05eventK018deviceInfoProvider013accountHeaderO009odiDeviceN0ACSb_SSSgS2SAA0s11InformationO0_pAA026ConfigurableAccountRequestqO0_pAA09ODIDevicenO0_pSgtYaKcfC
+ _$s17CoreODIEssentials25TrustInsightsServerClientV9isSandbox3mid14conversationId05eventK018deviceInfoProvider013accountHeaderO009odiDeviceN0ACSb_SSSgS2SAA0s11InformationO0_pAA026ConfigurableAccountRequestqO0_pAA09ODIDevicenO0_pSgtYaKcfCTu
+ _$sScTss5NeverORs_rlE5valuexvg
+ _$sScTss5NeverORs_rlE5valuexvgTu
- _$s17CoreODIEssentials23ODIiCloudAccountManagerCAA0E21RequestHeaderProviderAAWP
- _$s17CoreODIEssentials25TrustInsightsServerClientV9isSandbox3mid14conversationId05eventK018deviceInfoProvider013accountHeaderO009odiDeviceN0ACSb_SSSgS2SAA0s11InformationO0_pAA014AccountRequestqO0_pAA09ODIDevicenO0_pSgtYaKcfC
- _$s17CoreODIEssentials25TrustInsightsServerClientV9isSandbox3mid14conversationId05eventK018deviceInfoProvider013accountHeaderO009odiDeviceN0ACSb_SSSgS2SAA0s11InformationO0_pAA014AccountRequestqO0_pAA09ODIDevicenO0_pSgtYaKcfCTu
CStrings:
+ "Failed to persist usage: "
+ "No global counter found for rate limiting, starting new"
+ "No per app counter found for rate limiting, starting new"
+ "Rate limit exceeded."
+ "Rate limited (global counter)"
+ "Sandbox mode detected; continuing evaluation despite exceeding rate limit"
+ "_TtC9riskdatad11RateLimiter"
+ "counterForApps"
+ "globalCounter"
+ "globalLimits"
+ "longestTimeIntervalSupported"
+ "per bundleId counter"
+ "perAppLimits"
+ "perBundleIdLimits"
+ "riskdatad/ODIRateLimit.swift"
+ "trustInsightsGlobalUsage"
+ "trustInsightsPerAppUsage"
```
