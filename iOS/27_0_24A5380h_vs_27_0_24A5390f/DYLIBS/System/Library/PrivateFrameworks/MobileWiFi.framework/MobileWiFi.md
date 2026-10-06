## MobileWiFi

> `/System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f88c` | `0x2f9dc` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0x5b00` | `0x5b20` | **`+0x20`** |
| `__TEXT.__cstring` | `0x46a7` | `0x46c1` | **`+0x1a`** |
| `__AUTH_CONST.__objc_intobj` | `0x6d8` | `0x6f0` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x758` | `0x768` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1110` | `0x1118` | **`+0x8`** |

### Other Changes

```diff

-2027.18.0.0.0
+2027.24.0.0.0

-  Functions: 1208
-  Symbols:   1872
-  CStrings:  881
+  Functions: 1211
+  Symbols:   1876
+  CStrings:  882
Symbols:
+ _OUTLINED_FUNCTION_78
+ _WiFiNetworkGetConnectivityAssistEnabled
+ _WiFiNetworkSetConnectivityAssistEnabled
+ _kWiFiNetworkConnectivityAssistEnabledKey
CStrings:
+ "ConnectivityAssistEnabled"
```
