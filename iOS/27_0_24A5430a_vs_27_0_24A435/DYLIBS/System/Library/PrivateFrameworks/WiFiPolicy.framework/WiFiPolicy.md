## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x25d0b` | `0x25d4b` | **`+0x40`** |
| `__TEXT.__text` | `0xe2d8c` | `0xe2dbc` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x20dc0` | `0x20de0` | **`+0x20`** |

### Other Changes

```diff

-  CStrings:  5322
+  CStrings:  5323
Functions:
~ _OUTLINED_FUNCTION_3 : 20 -> 12
~ sub_20316b3a4 -> sub_2037e839c : 256 -> 264
~ -[WFMeasure initWithType:andReason:prevTestedOptions:prevTestedTrafficClass:andInterfaceName:] : 1572 -> 1560
~ _OUTLINED_FUNCTION_2 : 12 -> 20
~ -[WiFiAirplaneLandingDetectorAnalytics buildAnalyticsEventDictionary:state:isAssociated:] : 1060 -> 1064
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 932 -> 964
~ __ZNSt3__16vectorIN6gloria6TileIdENS_9allocatorIS2_EEE6resizeEm : 300 -> 308
~ -[WiFiUsagePoorLinkSession roamCacheDidUpdate:] : 936 -> 940
~ -[WiFiUsageSession _generateState] : 984 -> 988
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
