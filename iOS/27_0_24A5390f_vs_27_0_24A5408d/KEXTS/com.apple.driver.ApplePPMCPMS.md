## com.apple.driver.ApplePPMCPMS

> `com.apple.driver.ApplePPMCPMS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__os_log` | `0x3eb3` | `0x3e7e` | **`-0x35`** |
| `__TEXT_EXEC.__text` | `0x5326c` | `0x53280` | **`+0x14`** |
| `__DATA_CONST.__auth_ptr` | `0x8` | `0x10` | **`+0x8`** |

### Other Changes

```diff

-1191.0.27.0.0
+1191.0.37.0.0

-  CStrings:  1858
+  CStrings:  1857
Functions:
~ __ZN12ApplePPMCPMS36updateTimestampsTracesAndShimBudgetsE16UniqueClientID_tP18CPMSPPMPowerBudgetP31DetailedThermalBudgetsForClientPj : 424 -> 484
~ __ZN12ApplePPMCPMS14triggerLoggingEy : 364 -> 396
~ __ZN12ApplePPMCPMS38prepareAndSendControlSnapshotTelemetryE36CPMSPPMControlStateSnapshotRingIndex : 552 -> 452
~ sub_fffffff00936c5cc -> sub_fffffff009356194 : 204 -> 208
~ sub_fffffff009390234 -> sub_fffffff009379e00 : 2320 -> 2328
~ sub_fffffff009391b9c -> sub_fffffff00937b770 : 1624 -> 1632
~ sub_fffffff0093921f4 -> sub_fffffff00937bdd0 : 1900 -> 1908
CStrings:
- "%s::%s:%s: Failed to allocate local snapshot rings\n\n"
```
