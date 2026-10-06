## DVTInstrumentsFoundation

> `/System/Library/PrivateFrameworks/DVTInstrumentsFoundation.framework/DVTInstrumentsFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4404` | `0xe46f8` | **`+0x2f4`** |
| `__TEXT.__cstring` | `0xf1bc` | `0xf29c` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x5e8f` | `0x5eff` | **`+0x70`** |
| `__AUTH_CONST.__cfstring` | `0x9f20` | `0x9f80` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x3500` | `0x3540` | **`+0x40`** |
| `__TEXT.__gcc_except_tab` | `0x629c` | `0x6288` | **`-0x14`** |
| `__AUTH_CONST.__auth_got` | `0x2038` | `0x2048` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3e80` | `0x3e78` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0xe76` | `0xe7a` | **`+0x4`** |

### Other Changes

```diff

-64578.160.1.0.0
+64578.209.1.0.0

-  Functions: 5003
-  Symbols:   1877
-  CStrings:  2610
+  Functions: 5006
+  Symbols:   1882
+  CStrings:  2617
Symbols:
+ _DTProcessControlServiceOption_StandardInputFile
+ _DTXSpawnAuditedSubtask
+ _DVTAuditedCodeValidlyHoldsEntitlement
+ _DVTLaunchHelperProcessErrorDomain
+ _DVTRuntimeAnalysisHelperEntitlement
+ _posix_spawn_file_actions_addopen
- _DTXSpawnSubtaskWithError
CStrings:
+ "%@ is not trusted to analyze another process"
+ "B52@?0I8I12{?=[8I]}16i48"
+ "Unable to allocate process I/O pipes: %d"
+ "XRDeviceStandardInputFile"
+ "com.apple.private.runtime-analysis-helper"
+ "kperf_sample_off failed (%s)."
+ "posix_spawn failure while launching: %@ (Unable to allocate process I/O pipes %d)"
+ "refusing to vend task port for %d to untrusted agent %{public}s[%d]: %{public}s"
+ "v56@?0I8I12I16{?=[8I]}20i52"
- "Unable to allocate process I/O pipes %d"
- "v16@?0I8I12"
```
