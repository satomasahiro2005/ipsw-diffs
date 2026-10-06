## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fed90` | `0x1ff0bc` | **`+0x32c`** |
| `__TEXT.__cstring` | `0x25616` | `0x258ab` | **`+0x295`** |
| `__AUTH_CONST.__cfstring` | `0x1d060` | `0x1d1e0` | **`+0x180`** |
| `__TEXT.__gcc_except_tab` | `0x75ec` | `0x7694` | **`+0xa8`** |
| `__DATA_CONST.__objc_arraydata` | `0x2030` | `0x2080` | **`+0x50`** |
| `__TEXT.__unwind_info` | `0x6da0` | `0x6dc8` | **`+0x28`** |

### Other Changes

```diff

-1030.81.0.0.0
+1030.84.4.1.0

-  Functions: 9446
+  Functions: 9449

-  CStrings:  6350
+  CStrings:  6362
CStrings:
+ "-[CWFXPCRequestProxy activate]_block_invoke_4"
+ "com.apple.wifi.managed.0B2FD749-B328-434F-B545-F623DD66BEB6"
+ "com.apple.wifi.managed.0E6EFC11-3A3C-4180-955E-356E715DB3C3"
+ "com.apple.wifi.managed.2062CBA7-23E6-4BF1-B9C4-268139514512"
+ "com.apple.wifi.managed.3C4C6DD2-2D0D-4A70-B98C-B86783CEAE8B"
+ "com.apple.wifi.managed.55ED3A1A-8C5C-4D88-ACD6-38650431963E"
+ "com.apple.wifi.managed.6ABE30A2-F5D9-4E0E-947D-A602509A9143"
+ "com.apple.wifi.managed.849B9773-8616-4840-B266-1F16E70D2973"
+ "com.apple.wifi.managed.95D56CC3-4631-40A1-89C7-0C6F6DBCC241"
+ "com.apple.wifi.managed.B4BB6F74-DD2C-49FF-A071-33F14B2ABC45"
+ "com.apple.wifi.managed.D0C72AA6-0DDC-4FFE-9C20-B0FFAD7F5AB8"
+ "performAutoJoin"
+ "timeUnassocSkippedPartiallyMatchedCandidate"
+ "timeUnassocSkippedPartiallyMatchedCandidatePerc"
+ "wifiNetworkSharingUpdateKnownNetwork"
- "-[CWFXPCRequestProxy activate]_block_invoke_3"
- "timeUnassocSkippedPartialMatchCandidate"
- "timeUnassocSkippedPartialMatchCandidatePerc"
```
