## AppleMediaServicesKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesKitInternal.framework/AppleMediaServicesKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x60c924` | `0x60ab60` | **`-0x1dc4`** |
| `__TEXT.__cstring` | `0xd52d` | `0xdb24` | **`+0x5f7`** |
| `__TEXT.__eh_frame` | `0x4644` | `0x4454` | **`-0x1f0`** |
| `__TEXT.__oslogstring` | `0xe7b` | `0xc9c` | **`-0x1df`** |
| `__AUTH_CONST.__const` | `0x26e30` | `0x26ff0` | **`+0x1c0`** |
| `__TEXT.__gcc_except_tab` | `0x2d3fc` | `0x2d4c0` | **`+0xc4`** |
| `__AUTH.__objc_data` | `0xcb8` | `0xc00` | **`-0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x3698` | `0x3608` | **`-0x90`** |
| `__TEXT.__const` | `0x53828` | `0x538a8` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0xd858` | `0xd7e0` | **`-0x78`** |
| `__DATA.__data` | `0x1ba0` | `0x1b40` | **`-0x60`** |
| `__TEXT.__swift5_typeref` | `0x1c04` | `0x1ba8` | **`-0x5c`** |
| `__DATA_CONST.__objc_selrefs` | `0xa70` | `0xa38` | **`-0x38`** |
| `__TEXT.__constg_swiftt` | `0x12c8` | `0x129c` | **`-0x2c`** |
| `__AUTH.__data` | `0x4f8` | `0x4d0` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1478` | `0x1450` | **`-0x28`** |
| `__TEXT.__objc_methlist` | `0xffc` | `0xfdc` | **`-0x20`** |
| `__TEXT.__swift_as_cont` | `0x488` | `0x468` | **`-0x20`** |
| `__TEXT.__swift5_fieldmd` | `0x108c` | `0x1070` | **`-0x1c`** |
| `__TEXT.__swift5_capture` | `0x1f8` | `0x1e4` | **`-0x14`** |
| `__TEXT.__swift5_reflstr` | `0xb73` | `0xb63` | **`-0x10`** |
| `__TEXT.__swift_as_ret` | `0x240` | `0x234` | **`-0xc`** |
| `__DATA_CONST.__got` | `0x668` | `0x660` | **`-0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1c0` | `0x1b8` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x88` | `0x80` | **`-0x8`** |
| `__DATA_CONST.__objc_protorefs` | `0x30` | `0x28` | **`-0x8`** |
| `__DATA_DIRTY.__data` | `0x4a8` | `0x4a0` | **`-0x8`** |
| `__TEXT.__swift_as_entry` | `0x248` | `0x240` | **`-0x8`** |
| `__TEXT.__swift5_types` | `0x1c4` | `0x1c0` | **`-0x4`** |

### Other Changes

```diff

-2.0.18.0.0
+2.0.21.0.0

+  - /System/Library/Frameworks/ImageIO.framework/ImageIO

-  Functions: 10619
-  Symbols:   663
-  CStrings:  2031
+  Functions: 10612
+  Symbols:   661
+  CStrings:  2085
Symbols:
+ _CGImageSourceCopyPropertiesAtIndex
+ _CGImageSourceCreateWithData
+ _kCGImagePropertyPixelHeight
- _NSLocalizedDescriptionKey
- _OBJC_CLASS_$_NSDateFormatter
- _OBJC_CLASS_$__TtC29AppleMediaServicesKitInternal14JetpackFetcher
- _OBJC_METACLASS_$__TtC29AppleMediaServicesKitInternal14JetpackFetcher
- _swift_retain_x27
CStrings:
+ " bottom="
+ " flippedY="
+ " height="
+ "); passing raw crop rect"
+ "2.0.21"
+ "Account image crop rect Y out of bounds after flip (imageHeight="
+ "Missing platform specific identifier"
+ "accountMissing"
+ "ams.channellink"
+ "ams.icloud"
+ "ams.jni"
+ "ams.purchase"
+ "ams.webcontainer"
+ "androidErrnoException"
+ "authenticationFailed"
+ "channelLinkFailed"
+ "channelLinkInvalidBody"
+ "channelLinkParamsMissing"
+ "channelLinkServerError"
+ "dialogActionParseFailed"
+ "failedToGetAccountFromContext"
+ "failedToGetAccountFromDSID"
+ "failedToGetJSAccount"
+ "featureNotSupported"
+ "fetchMetricsIdentifierActionInvalidArgument"
+ "fetchMetricsIdentifierActionMissingProvider"
+ "fetchMetricsIdentifierActionParseFailed"
+ "fetchMetricsIdentifierActionRunFailed"
+ "includeAuthKitTokensNotSupported"
+ "includeiCloudTokensNotSupported"
+ "inlineAuthenticationFailed"
+ "invalidAccountState"
+ "invalidPageModel"
+ "jniCallBooleanMethodFailed"
+ "jniCallLongMethodFailed"
+ "jniCallObjectMethodFailed"
+ "jniCallVoidMethodFailed"
+ "jniFindClassFailed"
+ "jniFindObjectFieldFailed"
+ "jniFindStaticObjectFieldFailed"
+ "jniFindStaticObjectFieldNullableFailed"
+ "jniGetFieldIdFailed"
+ "jniGetIntFieldFailed"
+ "jniGetLongFieldFailed"
+ "jniGetMethodIdFailed"
+ "jniGetObjectClass"
+ "jniGetObjectFieldFailed"
+ "jniGetObjectFieldNullableFailed"
+ "jniGetStaticFieldFailed"
+ "jniGetStaticMethodID"
+ "jniGetStaticObjectFieldFailed"
+ "jniGetStringArrayFieldFailed"
+ "jniNewObjectFailed"
+ "jniStaticObjectMethodFailed"
+ "keybag"
+ "makeMediaTokenFailed"
+ "mescalNotSupported"
+ "metricsActionFailedToEnqueueMetrics"
+ "mismatchAccountDSID"
+ "mismatchAccountIdentifier"
+ "networkActionExecuteFailed"
+ "networkActionInvalidHeader"
+ "networkActionInvalidMethod"
+ "networkActionInvalidUrl"
+ "networkActionParseFailed"
+ "networkActionParseResultFailed"
+ "networkActionRunFailed"
+ "productCodeMissing"
+ "purchaseFailed"
+ "requiresCellularAccessNotSupported"
+ "resolveFailed"
+ "storefrontMissing"
+ "unknownExceptionType"
+ "unsupportedRegion"
+ "usePrimaryKeychainNotSupported"
- "2.0.18"
- "Caching source to %s"
- "EEE, dd MMM yyyy HH:mm:ss zzz"
- "Failed download (response: "
- "Failed download (response: %@)"
- "Failed download with error: %@"
- "Failed to cache source: %@"
- "Failed to fetch and cache Jetpack with error = %@"
- "Fetching Jetpack..."
- "If-Modified-Since"
- "If-Modified-Since: %s"
- "Jetpack URL not found in bag"
- "Jetpack successfully fetched and written to %s"
- "Removing old cache at %s"
- "Response returned unexpected status code: "
- "Source has not changed since last requested. Skipping caching"
- "Status code returned from request: %ld"
- "Unable to create URL from string: "
- "Unexpected status code: %ld"
- "cacheTask(url:outputFileURL:)"
- "transportKeyAny"
```
