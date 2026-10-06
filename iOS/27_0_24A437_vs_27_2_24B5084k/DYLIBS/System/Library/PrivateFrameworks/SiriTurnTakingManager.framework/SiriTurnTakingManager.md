## SiriTurnTakingManager

> `/System/Library/PrivateFrameworks/SiriTurnTakingManager.framework/SiriTurnTakingManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24608` | `0x25054` | **`+0xa4c`** |
| `__TEXT.__oslogstring` | `0x1cc2` | `0x1e02` | **`+0x140`** |
| `__AUTH_CONST.__const` | `0x21a0` | `0x2238` | **`+0x98`** |
| `__TEXT.__const` | `0x1374` | `0x1404` | **`+0x90`** |
| `__TEXT.__constg_swiftt` | `0xb1c` | `0xbac` | **`+0x90`** |
| `__TEXT.__swift5_typeref` | `0x670` | `0x6ee` | **`+0x7e`** |
| `__TEXT.__swift5_fieldmd` | `0xabc` | `0xb04` | **`+0x48`** |
| `__AUTH_CONST.__objc_const` | `0x970` | `0x9b0` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x270` | `0x2b0` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0xb08` | `0xb38` | **`+0x30`** |
| `__TEXT.__eh_frame` | `0x798` | `0x768` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x645` | `0x675` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x980` | `0x9a0` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x36c` | `0x384` | **`+0x18`** |
| `__TEXT.__swift5_proto` | `0xdc` | `0xe4` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x1c` | `0x24` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x848` | `0x850` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0xa4` | `0xa8` | **`+0x4`** |

### Other Changes

```diff

-3520.27.1.0.0
+3605.4.1.0.0

+  - /System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/CoreSpeechFoundation

-  Functions: 1014
-  Symbols:   576
-  CStrings:  168
+  Functions: 1029
+  Symbols:   590
+  CStrings:  171
Symbols:
+ _OBJC_CLASS_$_CSUtils
+ _OBJC_CLASS_$_SLNCThresholdConfiguration
+ ___swift_closure_destructor.51Tm
+ ___swift_mutable_project_boxed_opaque_existential_1
+ _objc_retain_x23
+ _objc_retain_x24
+ _swift_makeBoxUnique
+ _swift_retain_x1
+ _symbolic $s21SiriTurnTakingManager15CSUtilsProviderP
+ _symbolic $s21SiriTurnTakingManager16SLUresMitigatingP
+ _symbolic So26SLNCThresholdConfigurationCSg
+ _symbolic _____ 21SiriTurnTakingManager22DefaultCSUtilsProviderV
+ _symbolic ______p 21SiriTurnTakingManager15CSUtilsProviderP
+ _symbolic ______pSg 21SiriTurnTakingManager16SLUresMitigatingP
+ _symbolic x
- _symbolic So15SLUresMitigatorCSg
CStrings:
+ "Completion block of getMitigationAsset invoked and ncThresholdConfiguration is cached"
+ "fetching mitigation asset from MitigationAssetProvider with error: %s"
+ "processTTCandidate: usingConfigThresholds=%{bool}d, selfPlatform=%lu, mode=%lu"
+ "using config path - %s for loading NC (bnnsIrPath empty=%{bool}d, ncThresholdConfiguration=%{bool}d)"
- "using config path - %s for loading NC"
```
