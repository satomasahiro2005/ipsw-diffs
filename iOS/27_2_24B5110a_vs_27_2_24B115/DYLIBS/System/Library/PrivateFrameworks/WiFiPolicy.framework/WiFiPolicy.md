## WiFiPolicy

> `/System/Library/PrivateFrameworks/WiFiPolicy.framework/WiFiPolicy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x25deb` | `0x25e2b` | **`+0x40`** |
| `__AUTH_CONST.__cfstring` | `0x20e40` | `0x20e60` | **`+0x20`** |
| `__TEXT.__text` | `0xe3c94` | `0xe3c90` | **`-0x4`** |
| `__DATA.__bss` | `0x49` | `0x48` | **`-0x1`** |

### Other Changes

```diff

-  Symbols:   12038
-  CStrings:  5327
+  Symbols:   12037
+  CStrings:  5328
Symbols:
- __isSeedInstall
Functions:
~ -[WFMeasure initWithType:andReason:prevTestedOptions:prevTestedTrafficClass:andInterfaceName:] : 1572 -> 1560
~ -[WiFiUsageLinkSession performLinkTestFor:isTriggeredByFault:] : 932 -> 964
~ -[WiFiUsageSession _generateState] : 984 -> 988
~ +[WiFiUsagePrivacyFilter initialize] : 52 -> 40
~ +[WiFiUsagePrivacyFilter isInternalOrSeedInstall] : 28 -> 12
CStrings:
+ "%s Rejected due to [WiFiUsagePrivacyFilter isInternalInstall]\n"
```
