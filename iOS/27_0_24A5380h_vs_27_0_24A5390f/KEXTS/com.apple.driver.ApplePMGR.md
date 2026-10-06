## com.apple.driver.ApplePMGR

> `com.apple.driver.ApplePMGR`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x62100` | `0x625fc` | **`+0x4fc`** |
| `__TEXT.__cstring` | `0xfedb` | `0x1011c` | **`+0x241`** |
| `__DATA_CONST.__kalloc_var` | `0xfa0` | `0xff0` | **`+0x50`** |

### Other Changes

```diff

-1976.0.8.0.0
-  Functions: 2855
+1976.0.10.0.0
+  Functions: 2866

-  CStrings:  1802
+  CStrings:  1810
CStrings:
+ "(PerfState)minPerfState < maxPerfStates"
+ "PerfState ApplePMGR::_getPerfDomainCurrentState(PerfDomainID, UInt32)"
+ "_die < _target->getDieCount()"
+ "perfDomain->devicePerfStateRequirements[die]"
+ "site.DeviceIDMask *"
+ "virtual IOReturn ApplePMGRFunctionGetValidPerfState::callFunction(void *, void *, void *)"
+ "virtual bool ApplePMGRFunctionGetValidPerfState::initWithTargetDataAndSymbol(IOService *, const OSData *, const OSSymbol *)"
+ "virtual bool ApplePMGRFunctionSetPerfState::initWithTargetDataAndSymbol(IOService *, const OSData *, const OSSymbol *)"
+ "void ApplePMGR::_updateDevicePerfDomainRequirementsGated(uintptr_t, uintptr_t, uintptr_t, uintptr_t)"
- "PerfState ApplePMGR::_getPerfDomainCurrentState(PerfDomainID)"
```
