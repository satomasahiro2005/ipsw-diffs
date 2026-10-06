## com.apple.driver.AppleDCP

> `com.apple.driver.AppleDCP`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x3d0` | **`+0x3d0`** |
| `__TEXT_EXEC.__text` | `0x8108` | `0x8128` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1d67` | `0x1d74` | **`+0xd`** |

### Other Changes

```diff

-1303.0.0.502.1
+1317.0.3.0.5
Functions:
~ sub_fffffff008a64350 -> sub_fffffff008a7cad0 : 276 -> 292
~ _OUTLINED_FUNCTION_0 : 108 -> 132
~ sub_fffffff008a66ab8 -> sub_fffffff008a7f260 : 60 -> 56
~ __ZN14AppleDCPExpert20_failSafeStatsToDictEP18HealthMonitorStats : 684 -> 680
CStrings:
+ "v60@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{IOWorkLoop}^{OSArray}B}16^v24i32Q36r^v44Q52"
- "v60@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{AFKEndpointInterface=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}^{AFKUserDataPipe}^{IOService}^{OSArray}B}16^v24i32Q36r^v44Q52"
```
