## servicesintelligenced

> `/System/Library/PrivateFrameworks/ServicesIntelligence.framework/servicesintelligenced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x139a0` | `0x165f4` | **`+0x2c54`** |
| `__TEXT.__eh_frame` | `0x1078` | `0x1408` | **`+0x390`** |
| `__TEXT.__unwind_info` | `0x4e8` | `0x5b8` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0xc50` | `0xcc0` | **`+0x70`** |
| `__TEXT.__const` | `0x302` | `0x36a` | **`+0x68`** |
| `__TEXT.__swift_as_cont` | `0xe8` | `0x134` | **`+0x4c`** |
| `__DATA.__objc_const` | `0x1d8` | `0x218` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0xe5c` | `0xe9c` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x630` | `0x668` | **`+0x38`** |
| `__DATA_CONST.__got` | `0x230` | `0x268` | **`+0x38`** |
| `__TEXT.__cstring` | `0x5c8` | `0x5f8` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x487` | `0x4b0` | **`+0x29`** |
| `__TEXT.__swift_as_ret` | `0xac` | `0xd0` | **`+0x24`** |
| `__TEXT.__swift5_reflstr` | `0x43` | `0x5c` | **`+0x19`** |
| `__TEXT.__swift5_fieldmd` | `0x44` | `0x5c` | **`+0x18`** |
| `__DATA.__data` | `0x2c0` | `0x2d0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0x193` | `0x1a3` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x68` | `0x74` | **`+0xc`** |
| `__DATA_CONST.__auth_ptr` | `0xb0` | `0xb8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-1.69.0.0.0
+1.77.0.0.0

-  Functions: 285
-  Symbols:   309
-  CStrings:  162
+  Functions: 325
+  Symbols:   324
+  CStrings:  164
Symbols:
+ _$s20ServicesIntelligence0aB8ProviderC17runUseCaseGuarded_14requestContextAA03RuneF8ResponseVSgAA0jeF7RequestV_AA0lI0VSgtYaKF
+ _$s20ServicesIntelligence0aB8ProviderC17runUseCaseGuarded_14requestContextAA03RuneF8ResponseVSgAA0jeF7RequestV_AA0lI0VSgtYaKFTu
+ _$s20ServicesIntelligence0aB8ProviderC26processActiveAccountChangeyyYaF
+ _$s20ServicesIntelligence0aB8ProviderC26processActiveAccountChangeyyYaFTu
+ _$s20ServicesIntelligence0aB8ProviderCAA20PerformanceTrackableAAMc
+ _$s20ServicesIntelligence11RequestTypeO25dailySystemBackgroundTaskyA2CmFWC
+ _$s20ServicesIntelligence11RequestTypeO29semanticProfileBackgroundTaskyA2CmFWC
+ _$s20ServicesIntelligence11RequestTypeO40postInstallSemanticProfileBackgroundTaskyA2CmFWC
+ _$s20ServicesIntelligence11RequestTypeOMa
+ _$s20ServicesIntelligence12MetricsTopicO8allCasesSayACGvgZ
+ _$s20ServicesIntelligence14RequestContextV4from_13correlationIDAcA0C4TypeO_SSSgtYaFZ
+ _$s20ServicesIntelligence14RequestContextV4from_13correlationIDAcA0C4TypeO_SSSgtYaFZTu
+ _$s20ServicesIntelligence20PerformanceTrackablePAAE05trackC011requestType0F7Context7useCase9operationqd__AA07RequestG0O_AA0lH0VSSSgqd__yYaXEtYalF
+ _$s20ServicesIntelligence20PerformanceTrackablePAAE05trackC011requestType0F7Context7useCase9operationqd__AA07RequestG0O_AA0lH0VSSSgqd__yYaXEtYalFTu
+ _$sScTss5NeverORs_rlE5valuexvg
+ _$sScTss5NeverORs_rlE5valuexvgTu
+ _$ss5NeverOMn
+ _objc_release_x28
+ _objc_retain_x28
+ _swift_release_x21
- _$s20ServicesIntelligence0aB8ProviderC17runUseCaseGuardedyAA03RuneF8ResponseVSgAA0heF7RequestVYaKF
- _$s20ServicesIntelligence0aB8ProviderC17runUseCaseGuardedyAA03RuneF8ResponseVSgAA0heF7RequestVYaKFTu
- _$s20ServicesIntelligence12MetricsTopicO8platformyA2CmFWC
- _objc_retain_x24
- _swift_bridgeObjectRelease_n
CStrings:
+ "[%s]: Failed to flush topic %s from container %s: %s"
+ "[%s]: Flushed %@ events for topic %s from container: %s"
+ "_startupTask"
+ "computeSampledAdamId(requestContext:)"
+ "computeSemanticProfile(requestContext:)"
+ "executeSemanticProfileWorkload(bookkeeper:requestContext:)"
+ "startupLock"
- "[%s]: %s"
- "[%s]: Flushed %@ events from container: %s"
- "computeSampledAdamId()"
- "computeSemanticProfile()"
- "executeSemanticProfileWorkload(bookkeeper:)"
```
