## AVRouting

> `/System/Library/Frameworks/AVRouting.framework/AVRouting`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x63edc` | `0x63f34` | **`+0x58`** |
| `__TEXT.__cstring` | `0xed51` | `0xed92` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x4660` | `0x46a0` | **`+0x40`** |
| `__DATA_CONST.__const` | `0x1270` | `0x1278` | **`+0x8`** |

### Other Changes

```diff

-360.66.1.11.1
+360.70.2.0.0

-  Symbols:   4649
-  CStrings:  1709
+  Symbols:   4650
+  CStrings:  1711
Symbols:
+ _AVOutputContextManagerFailureDetailsMediaAppNameKey
Functions:
~ -[AVFigEndpointUIAgentOutputContextManagerImpl _showErrorPromptForRouteDescriptor:reason:didFailToConnectToOutputDeviceDictionary:failureDetails:] : 992 -> 1080
CStrings:
+ "AVOutputContextManagerFailureDetailsMediaAppNameKey"
+ "MediaAppName"
```
