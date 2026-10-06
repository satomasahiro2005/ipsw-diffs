## MobileWiFi

> `/System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2f9dc` | `0x2fa68` | **`+0x8c`** |
| `__AUTH_CONST.__auth_got` | `0x788` | `0x790` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x768` | `0x770` | **`+0x8`** |

### Other Changes

```diff

-2027.32.0.0.0
+2029.6.0.0.0

-  Functions: 1211
-  Symbols:   1876
+  Functions: 1212
+  Symbols:   1878
Symbols:
+ _WiFiNetworkHasConnectivityAssistPreference
+ _objc_retain_x23
Functions:
- _OUTLINED_FUNCTION_5
~ _OUTLINED_FUNCTION_5 : 20 -> 12
~ _OUTLINED_FUNCTION_5 : 16 -> 20
~ _OUTLINED_FUNCTION_5 : 20 -> 16
+ _OUTLINED_FUNCTION_5
~ ___WiFiNetworkCreateCoreWiFiNetworkProfile : 6672 -> 6684
+ _WiFiNetworkHasConnectivityAssistPreference
~ ___WiFiNetworkCreateFromCoreWiFiNetworkProfile : 7656 -> 7716
```
