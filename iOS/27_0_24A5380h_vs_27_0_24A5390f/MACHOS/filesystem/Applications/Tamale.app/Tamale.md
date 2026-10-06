## Tamale

> `/Applications/Tamale.app/Tamale`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x103f40` | `0x101c18` | **`-0x2328`** |
| `__TEXT.__swift5_typeref` | `0x117a0` | `0x111c6` | **`-0x5da`** |
| `__TEXT.__eh_frame` | `0x4658` | `0x4540` | **`-0x118`** |
| `__DATA.__data` | `0x84e8` | `0x83d8` | **`-0x110`** |
| `__TEXT.__const` | `0xb434` | `0xb334` | **`-0x100`** |
| `__DATA.__objc_const` | `0x89f0` | `0x8940` | **`-0xb0`** |
| `__DATA_CONST.__const` | `0x7438` | `0x7398` | **`-0xa0`** |
| `__TEXT.__auth_stubs` | `0x5990` | `0x58f0` | **`-0xa0`** |
| `__TEXT.__unwind_info` | `0x31a8` | `0x3120` | **`-0x88`** |
| `__DATA_CONST.__auth_got` | `0x2cd0` | `0x2c80` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0xbf5` | `0xba5` | **`-0x50`** |
| `__TEXT.__swift5_capture` | `0x1808` | `0x17b8` | **`-0x50`** |
| `__TEXT.__swift5_reflstr` | `0x2e39` | `0x2de9` | **`-0x50`** |
| `__TEXT.__constg_swiftt` | `0x3b0c` | `0x3ac0` | **`-0x4c`** |
| `__TEXT.__swift5_fieldmd` | `0x2d60` | `0x2d2c` | **`-0x34`** |
| `__TEXT.__oslogstring` | `0x2247` | `0x2217` | **`-0x30`** |
| `__DATA_CONST.__got` | `0x1458` | `0x1430` | **`-0x28`** |
| `__TEXT.__swift_as_cont` | `0x2e8` | `0x2c4` | **`-0x24`** |
| `__DATA_CONST.__auth_ptr` | `0x13c8` | `0x13a8` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0x2316` | `0x2336` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x2700` | `0x26e0` | **`-0x20`** |
| `__TEXT.__swift_as_entry` | `0x168` | `0x154` | **`-0x14`** |
| `__DATA.__objc_data` | `0x1ec0` | `0x1ed0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x14c4` | `0x14d4` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x11c` | `0x10c` | **`-0x10`** |
| `__DATA_CONST.__objc_classlist` | `0x188` | `0x180` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x31c` | `0x318` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types2`

### Other Changes

```diff

-224.1.0.0.0
+234.0.0.0.0

-  Functions: 4393
-  Symbols:   2519
-  CStrings:  1505
+  Functions: 4354
+  Symbols:   2502
+  CStrings:  1502
Symbols:
- _$s12CoreLocation27CLBackgroundActivitySessionC10invalidateyyF
- _$s12CoreLocation27CLBackgroundActivitySessionCACycfc
- _$s12CoreLocation27CLBackgroundActivitySessionCMa
- _$s20VisualIntelligenceUI17OnboardingOverlayV7content14continueActionACyxGx_yyctcfC
- _$s20VisualIntelligenceUI17OnboardingOverlayVMn
- _$s20VisualIntelligenceUI17OnboardingOverlayVyxG05SwiftC04ViewAAMc
- _$s22VisualIntelligenceCore19UserDefaultsUtilityC15hasOnboardedAppSbvgTj
- _$s22VisualIntelligenceCore19UserDefaultsUtilityC15hasOnboardedAppSbvsTj
- _$s31VisualIntelligenceCameraSupport0C13MotionMonitorC12currentStateAC0eH0OvgTj
- _$s7SwiftUI4ViewPAAE8staticIf_4then4elseQrqd___qd_0_xXEqd_1_xXEtAA0C14InputPredicateRd__AaBRd_0_AaBRd_1_r1_lF
- _$s7SwiftUI4ViewPAAE8staticIf_4then4elseQrqd___qd_0_xXEqd_1_xXEtAA0C14InputPredicateRd__AaBRd_0_AaBRd_1_r1_lFQOMQ
- _$s7SwiftUI7CapsuleVMa
- _$s7SwiftUI8MaterialVMa
- _$s7SwiftUI8SolariumVAA18ViewInputPredicateAAWP
- _$s7SwiftUI8SolariumVACycfC
- _$s7SwiftUI8SolariumVMn
- _$s7SwiftUI8SolariumVN
CStrings:
+ "Deferring World->Geo session restart; runState=%s. Geo config applies on next resume via startInternal()."
+ "session:didChangeViewRotationAngle:"
+ "v32@0:8@\"ARSession\"16d24"
- "Ignoring shutter button while content is blurred"
- "Not showing onboarding because the user has already onboarded."
- "Showing app onboarding"
- "_TtC6TamaleP33_496EA42FE05FE07634A3AC62A349A9F626FrameSynchronizerContainer"
- "consumer"
- "setBool:forKey:"
```
