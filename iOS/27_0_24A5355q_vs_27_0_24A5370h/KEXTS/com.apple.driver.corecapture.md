## com.apple.driver.corecapture

> `com.apple.driver.corecapture`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x750` | **`+0x750`** |
| `__TEXT_EXEC.__text` | `0x27c84` | `0x27ecc` | **`+0x248`** |

### Other Changes

```diff

-1355.39.0.0.0
+1355.41.0.0.0
Functions:
~ __ZN6CCPipe24createReportersAndLegendEPKc : 644 -> 660
~ __Z27createInterestListFromArrayP7OSArrayiPm : 1112 -> 1144
~ __ZN11CCIOService20CCSetProperties_ImplEP12OSDictionary : 1504 -> 1492
~ __Z25createInterestsDictionaryP20IOReportInterestList : 2304 -> 2324
~ __ZN8CCStream24createReportersAndLegendEv : 416 -> 424
~ __ZN20CCDataPipeUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 480 -> 524
~ __ZN13CCFaultReport12saveFileNameEPKc : 176 -> 188
~ __ZN13CCFaultReport17initWithFaultInfoEiPKcPvjS1_S1_j : 628 -> 636
~ sub_fffffff00a98bc90 -> sub_fffffff00aa2cfa0 : 84 -> 92
~ __ZN15CCFaultReporter24dumpClientListAndHistoryEv : 368 -> 388
~ __ZN15CCFaultReporter19createHistoryStringEv : 668 -> 728
~ __ZN15CCFaultReporter19reportFaultWithInfoEiPKcjS1_S1_jP12OSDictionary : 1336 -> 1364
~ __ZN15CCFaultReporter12processFaultEP13CCFaultReport : 1700 -> 1728
~ sub_fffffff00a990f14 -> sub_fffffff00aa322b4 : 360 -> 380
~ __ZN15CCFaultReporter15updateRegisteryEv : 452 -> 480
~ sub_fffffff00a991240 -> sub_fffffff00aa32610 : 400 -> 496
~ __ZN15CCFaultReporter18updateReasonStringEPKc : 684 -> 712
~ sub_fffffff00a994714 -> sub_fffffff00aa35b60 : 212 -> 240
~ sub_fffffff00a9947e8 -> sub_fffffff00aa35c50 : 216 -> 232
~ __ZN9CCLogPipe19resizeScratchBufferEPcmPm : 504 -> 516
~ sub_fffffff00a995f80 -> sub_fffffff00aa37404 : 300 -> 328
~ sub_fffffff00a9960ac -> sub_fffffff00aa3754c : 608 -> 616
~ __ZN9CCLogPipe7captureE11CCTimestampPKc : 1712 -> 1732
~ sub_fffffff00a99dfb0 -> sub_fffffff00aa3f46c : 1152 -> 1172
~ __ZN11CCIOService8DispatchE5IORPC : 2908 -> 2916
```
