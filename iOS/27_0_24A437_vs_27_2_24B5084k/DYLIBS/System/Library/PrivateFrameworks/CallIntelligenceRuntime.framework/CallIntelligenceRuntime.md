## CallIntelligenceRuntime

> `/System/Library/PrivateFrameworks/CallIntelligenceRuntime.framework/CallIntelligenceRuntime`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x77cb4` | `0x795f4` | **`+0x1940`** |
| `__TEXT.__oslogstring` | `0x2d33` | `0x2e73` | **`+0x140`** |
| `__TEXT.__eh_frame` | `0x4898` | `0x49c8` | **`+0x130`** |
| `__AUTH_CONST.__objc_const` | `0x2f30` | `0x2f90` | **`+0x60`** |
| `__TEXT.__swift5_reflstr` | `0x20c8` | `0x2118` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x19fe` | `0x1a48` | **`+0x4a`** |
| `__TEXT.__unwind_info` | `0x1b40` | `0x1b88` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x3828` | `0x3868` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x1bb4` | `0x1bf0` | **`+0x3c`** |
| `__AUTH_CONST.__auth_got` | `0x10b8` | `0x10e8` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x6b8` | `0x6e0` | **`+0x28`** |
| `__DATA_CONST.__objc_selrefs` | `0x530` | `0x550` | **`+0x20`** |
| `__TEXT.__cstring` | `0x20e1` | `0x2101` | **`+0x20`** |
| `__TEXT.__swift_as_cont` | `0x304` | `0x318` | **`+0x14`** |
| `__AUTH.__data` | `0x2098` | `0x20a8` | **`+0x10`** |
| `__DATA.__data` | `0x11c8` | `0x11d8` | **`+0x10`** |
| `__TEXT.__const` | `0x4d74` | `0x4d84` | **`+0x10`** |
| `__TEXT.__swift_as_ret` | `0x194` | `0x1a0` | **`+0xc`** |
| `__TEXT.__swift_as_entry` | `0x198` | `0x19c` | **`+0x4`** |

### Other Changes

```diff

-153.100.1.2.29
+156.200.70.2.2

+  - /System/Library/PrivateFrameworks/AgentSessionKit.framework/AgentSessionKit

-  Functions: 1865
-  Symbols:   971
-  CStrings:  358
+  Functions: 1877
+  Symbols:   978
+  CStrings:  362
Symbols:
+ _OBJC_CLASS_$_NSNumberFormatter
+ _OBJC_CLASS_$_NSRegularExpression
+ _symbolic _____ 16FoundationModels19SystemLanguageModelC
+ _symbolic _____SSYaYbKcSg 23CallIntelligenceRuntime17WaitTimeAFMResultV
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic ___________SStYbc 16FoundationModels20LanguageModelSessionC AA06SystemcD0C
+ _symbolic _____y_____G 2os21OSAllocatedUnfairLockV 16FoundationModels20LanguageModelSessionC
+ _symbolic _____y__________G s13ManagedBufferCsRi__rlE 16FoundationModels20LanguageModelSessionC So16os_unfair_lock_sV
- _symbolic _____ 16FoundationModels20LanguageModelSessionC
CStrings:
+ "WaitTimeProvider: discarding queue position prediction; predicted value not present in utterance."
+ "WaitTimeProvider: discarding wait time prediction; predicted value not present in utterance."
+ "WaitTimeProvider: session transcript exceeded context window size; starting a new session and retrying."
+ "callNotesCompactions.sqlitedb"
```
