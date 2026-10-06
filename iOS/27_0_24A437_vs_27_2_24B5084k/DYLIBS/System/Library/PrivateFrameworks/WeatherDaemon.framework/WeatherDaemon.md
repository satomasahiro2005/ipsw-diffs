## WeatherDaemon

> `/System/Library/PrivateFrameworks/WeatherDaemon.framework/WeatherDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x240c74` | `0x242198` | **`+0x1524`** |
| `__TEXT.__cstring` | `0x3ec5` | `0x4245` | **`+0x380`** |
| `__AUTH_CONST.__const` | `0x142d0` | `0x141b8` | **`-0x118`** |
| `__TEXT.__oslogstring` | `0xd3b5` | `0xd4a5` | **`+0xf0`** |
| `__TEXT.__swift5_capture` | `0x28b4` | `0x2850` | **`-0x64`** |
| `__DATA.__data` | `0x31b0` | `0x3200` | **`+0x50`** |
| `__TEXT.__swift5_typeref` | `0x5f96` | `0x5fdc` | **`+0x46`** |
| `__TEXT.__const` | `0x1aeb8` | `0x1aef8` | **`+0x40`** |
| `__DATA_DIRTY.__data` | `0x8170` | `0x8190` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x1138` | `0x1150` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x9148` | `0x9160` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x5d0` | `0x5e0` | **`+0x10`** |

### Other Changes

```diff

-1454.1.0.0.0
+1470.0.0.0.0

-  Functions: 15341
-  Symbols:   3962
-  CStrings:  1337
+  Functions: 15361
+  Symbols:   3971
+  CStrings:  1349
Symbols:
+ _NSLocalizedDescriptionKey
+ _NSLocalizedFailureReasonErrorKey
+ _NSLocalizedRecoverySuggestionErrorKey
+ _symbolic _____Sg 10Foundation12URLQueryItemV
+ _symbolic _____XDXMT 13WeatherDaemon31WDSJWTAuthenticatorServiceProxyC
+ _symbolic _____XDXMT 13WeatherDaemon34WDSJWTAuthenticatorServiceListenerC
+ _symbolic _____yS2SG s17_NativeDictionaryV
+ _symbolic _____ySS_SStG s23_ContiguousArrayStorageC
+ _symbolic _____ySSypG s18_DictionaryStorageC
CStrings:
+ " for the token request."
+ "Check the network connection and try the request again."
+ "Failed to generate token. bundleIdentifier=%{public}s, error=%{public}s"
+ "Failed to purge all lastFetch data; error=%{private,mask.hash}s"
+ "Failed to purge lastFetch data, error=%{private,mask.hash}s"
+ "Purged stale lastFetch data"
+ "The Apple Weather service returned HTTP "
+ "The Apple Weather service returned an unexpected response to the token request."
+ "The most common cause is that the WeatherKit App Service is not enabled for this app's App ID. WeatherKit has to be enabled in both the \"App Services\" tab and the \"App Capabilities\" tab of the App ID in Certificates, Identifiers & Profiles (https://developer.apple.com/account/resources/identifiers). Enabling it under \"App Capabilities\" also requires rebuilding the app with a regenerated provisioning profile. See https://developer.apple.com/help/account/services/weatherkit/"
+ "The token request could not reach the Apple Weather service."
+ "WeatherKit could not generate an authentication token for "
+ "WeatherKit setup hint: %{public}s"
+ "weatherdaemon.useGlobalAirPollutionModel"
- "Failed to generate token with error: %{public}s"
```
