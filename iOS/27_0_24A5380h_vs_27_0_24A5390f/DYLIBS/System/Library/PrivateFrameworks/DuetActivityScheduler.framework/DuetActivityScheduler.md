## DuetActivityScheduler

> `/System/Library/PrivateFrameworks/DuetActivityScheduler.framework/DuetActivityScheduler`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3e758` | `0x3f118` | **`+0x9c0`** |
| `__AUTH_CONST.__cfstring` | `0x5060` | `0x5280` | **`+0x220`** |
| `__TEXT.__oslogstring` | `0x31da` | `0x32ed` | **`+0x113`** |
| `__AUTH_CONST.__objc_const` | `0x7ec8` | `0x7f88` | **`+0xc0`** |
| `__TEXT.__gcc_except_tab` | `0x1568` | `0x1624` | **`+0xbc`** |
| `__TEXT.__cstring` | `0x40f2` | `0x41a7` | **`+0xb5`** |
| `__TEXT.__objc_methlist` | `0x4988` | `0x4a00` | **`+0x78`** |
| `__DATA_CONST.__const` | `0xf10` | `0xf78` | **`+0x68`** |
| `__DATA_CONST.__objc_selrefs` | `0x28e8` | `0x2938` | **`+0x50`** |
| `__AUTH_CONST.__objc_intobj` | `0x210` | `0x228` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x12e8` | `0x1300` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x494` | `0x4a4` | **`+0x10`** |

### Other Changes

```diff

-2467.0.14.502.1
+2467.0.23.502.1

-  Functions: 1674
-  Symbols:   2825
-  CStrings:  982
+  Functions: 1689
+  Symbols:   2840
+  CStrings:  1004
Symbols:
+ -[_DASActivity domainPriority]
+ -[_DASActivity phase]
+ -[_DASActivity setDomainPriority:]
+ -[_DASActivity setPhase:]
+ -[_DASPlistParser domainPriorityCache]
+ -[_DASPlistParser isPhasedSchedulingActivity:]
+ -[_DASPlistParser phasedProcessingCache]
+ -[_DASPlistParser priorityForDomain:]
+ -[_DASPlistParser setDomainPriorityCache:]
+ -[_DASPlistParser setPhasedProcessingCache:]
+ GCC_except_table13
+ _OBJC_IVAR_$__DASActivity._domainPriority
+ _OBJC_IVAR_$__DASActivity._phase
+ _OBJC_IVAR_$__DASPlistParser._domainPriorityCache
+ _OBJC_IVAR_$__DASPlistParser._phasedProcessingCache
CStrings:
+ "AIML"
+ "Can't load allowlist plist for PhasedScheduling lookup"
+ "Can't load domains plist for domain %@"
+ "Health"
+ "Mail"
+ "Media"
+ "Messages"
+ "Missing or invalid Priority key for domain %@ in domains plist"
+ "Missing or invalid domain entry for %@ in domains plist"
+ "No string mapping for domain %ld; returning sentinel priority"
+ "PhasedScheduling"
+ "Photos"
+ "Priority"
+ "Proactive"
+ "Search"
+ "SensingConnectivity"
+ "Services"
+ "Siri"
+ "StorageTech"
+ "com.apple.dasd.domains.plist"
+ "domainPriority"
+ "phase"
```
