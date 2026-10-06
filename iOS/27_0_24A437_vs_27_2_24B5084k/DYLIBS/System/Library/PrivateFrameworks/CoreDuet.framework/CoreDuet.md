## CoreDuet

> `/System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18fcf8` | `0x1901a0` | **`+0x4a8`** |
| `__TEXT.__cstring` | `0x15d00` | `0x15d57` | **`+0x57`** |
| `__TEXT.__oslogstring` | `0x18e01` | `0x18dbb` | **`-0x46`** |
| `__TEXT.__gcc_except_tab` | `0x73ec` | `0x73e0` | **`-0xc`** |
| `__AUTH_CONST.__auth_got` | `0xa70` | `0xa78` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x11a0` | `0x11a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x8080` | `0x8088` | **`+0x8`** |

### Other Changes

```diff

-1971.0.0.0.0
+1974.0.1.0.0

+  - /System/Library/PrivateFrameworks/TCC.framework/TCC

-  Functions: 8792
-  Symbols:   13366
-  CStrings:  4651
+  Functions: 8794
+  Symbols:   13369
+  CStrings:  4655
Symbols:
+ _TCCAccessCopyBundleIdentifiersDisabledForService
+ __CDConvertPhoneNumberStringToASCII
+ _kTCCServiceSiriAccess
Functions:
~ ___64-[_CDSiriLearningSettings _startWithCallback:invokeCallbackNow:]_block_invoke : 728 -> 724
~ +[_CDSiriLearningSettings uncachedAllLearningDisabledBundleIDs] : 60 -> 104
+ _OUTLINED_FUNCTION_2
- _OUTLINED_FUNCTION_2
- _OUTLINED_FUNCTION_6
~ _OUTLINED_FUNCTION_2 : 16 -> 32
~ _OUTLINED_FUNCTION_2 : 28 -> 16
+ _OUTLINED_FUNCTION_2
~ +[_CDContactResolver normalizedStringFromContactString:] : 148 -> 180
+ _OUTLINED_FUNCTION_59
~ +[_CDContactResolver resolveContactIdentifier:usingStore:] : 588 -> 604
+ __CDConvertPhoneNumberStringToASCII
~ +[_CDContactResolver resolveContactIfPossibleFromContactIdentifierString:usingStore:] : 304 -> 332
~ -[_DKCoreDataStorage deleteStorageFor:] : 864 -> 788
+ __CDConvertPhoneNumberStringToASCII.cold.1
~ ___41+[_CDSiriLearningSettings sharedInstance]_block_invoke : 412 -> 452
~ -[_CDSiriLearningSettings _startWithCallback:invokeCallbackNow:] : 404 -> 464
~ -[_CDSiriLearningSettings startSanitizingKnowledgeStore:] : 124 -> 128
~ -[_CDSiriLearningSettings startSanitizingInteractionStore:] : 124 -> 128
~ -[_CDSiriLearningSettings stopSanitizing] : 172 -> 176
- -[_DKCoreDataStorage deleteStorageFor:].cold.2
CStrings:
+ "AppExclusions"
+ "Error checking Siri Learning access (errno %{darwin.errno}d). Attempting checks but they may not work."
+ "IntelligenceFlow"
+ "Process has access to Siri Learning toggles."
+ "Unable to access Siri Learning toggles. Disabling checks."
+ "com.apple.tcc.access.changed"
+ "com.apple.tccd"
+ "mach-lookup"
- "Creating shell PSC to truncate storage."
- "Error checking preferences access (errno %{darwin.errno}d). Attempting checks but they may not work."
- "Process has access to preferences for Siri Learning toggles."
- "Unable to access preferences for Siri Learning toggles. Disabling checks."
```
