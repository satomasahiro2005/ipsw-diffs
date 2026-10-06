## ApplePhotonDetectorServices

> `/System/Library/PrivateFrameworks/ApplePhotonDetectorServices.framework/ApplePhotonDetectorServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3f40` | `0x3f94` | **`+0x54`** |
| `__TEXT.__oslogstring` | `0x772` | `0x7bd` | **`+0x4b`** |

### Other Changes

```diff

-10.60.0.0.0
+10.61.0.0.0

-  CStrings:  99
+  CStrings:  100
Functions:
~ __Z30sendSynchronousXpcMsgWithReplyP13xpcConnection25ISPServicesRemoteProperty29ISPServicesRemotePropertyTypeP28ISPServicesRemotePropertySet : 1332 -> 1416
CStrings:
+ "%s: Missing ISP Driver version information in PropertyType Get, returning\n"
```
