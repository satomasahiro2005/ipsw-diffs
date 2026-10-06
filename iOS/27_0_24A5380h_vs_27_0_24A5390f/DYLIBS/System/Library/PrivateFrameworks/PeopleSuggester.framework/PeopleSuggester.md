## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/PeopleSuggester`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x127f88` | `0x128e34` | **`+0xeac`** |
| `__AUTH_CONST.__cfstring` | `0x7f960` | `0x7fc20` | **`+0x2c0`** |
| `__TEXT.__cstring` | `0x31473` | `0x315b4` | **`+0x141`** |
| `__TEXT.__oslogstring` | `0x11218` | `0x11318` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x7110` | `0x7148` | **`+0x38`** |
| `__DATA_CONST.__got` | `0xa30` | `0xa50` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xaeb4` | `0xaed4` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x35b8` | `0x35c8` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x818` | `0x820` | **`+0x8`** |

### Other Changes

```diff

-1962.0.1.0.0
+1967.0.0.0.0

-  Functions: 5357
-  Symbols:   7979
-  CStrings:  17914
+  Functions: 5363
+  Symbols:   7987
+  CStrings:  17939
Symbols:
+ +[_PSAppUsageUtilities _attachmentsContainWebURL:]
+ +[_PSAppUsageUtilities _defaultBrowserAppBundleID]
+ +[_PSAppUsageUtilities boostAppsForSourceBundleId:attachments:mapping:traceId:parentSpanId:]
+ +[_PSAppUsageUtilities mostUsedAppShareExtensionsWithAppBundleIdsToShareExtensionBundleIdsMapping:sourceBundleId:attachments:traceId:parentSpanId:sharesFromSourceToTargetBundle:appUsageDurations:]
+ -[_PSContactCatalog _attemptLoadContactCatalogCapturingAttributes:]
+ _NSFileSize
+ _UTTypeConformsTo
+ ___196+[_PSAppUsageUtilities mostUsedAppShareExtensionsWithAppBundleIdsToShareExtensionBundleIdsMapping:sourceBundleId:attachments:traceId:parentSpanId:sharesFromSourceToTargetBundle:appUsageDurations:]_block_invoke
+ _kUTTypeFileURL
+ _kUTTypePlainText
+ _kUTTypeURL
- +[_PSAppUsageUtilities boostAppsForSourceBundleId:]
- +[_PSAppUsageUtilities mostUsedAppShareExtensionsWithAppBundleIdsToShareExtensionBundleIdsMapping:sourceBundleId:sharesFromSourceToTargetBundle:appUsageDurations:]
- ___163+[_PSAppUsageUtilities mostUsedAppShareExtensionsWithAppBundleIdsToShareExtensionBundleIdsMapping:sourceBundleId:sharesFromSourceToTargetBundle:appUsageDurations:]_block_invoke
CStrings:
+ "(none)"
+ "Contact catalog root is not a dictionary; got %{public}@ (fileSize=%llu bytes)"
+ "Default browser lookup returned nil; LSApplicationWorkspace did not surface a handler for https URL"
+ "Default-browser boost: %{public}@ (browser %{public}@) for source %{public}@"
+ "attachmentSchemes"
+ "attachmentTexts"
+ "attachmentUTIs"
+ "boostFired"
+ "boostedExtensionCount"
+ "boostedExtensions"
+ "com.apple"
+ "defaultBrowser"
+ "defaultBrowserBoostEnd2End"
+ "fileNotFound"
+ "fileSizeBytes"
+ "hasWebURL"
+ "https://www.apple.com"
+ "isThirdParty"
+ "loadContactCatalog"
+ "nonDictionary"
+ "outcome"
+ "parseFailed"
+ "readFailed"
+ "rootClass"
+ "versionMismatch"
```
