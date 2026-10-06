## installd

> `/usr/libexec/installd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x740f0` | `0x77948` | **`+0x3858`** |
| `__TEXT.__cstring` | `0x19733` | `0x1a123` | **`+0x9f0`** |
| `__TEXT.__objc_methname` | `0xdb77` | `0xe087` | **`+0x510`** |
| `__DATA_CONST.__cfstring` | `0xaac0` | `0xae20` | **`+0x360`** |
| `__TEXT.__gcc_except_tab` | `0x3eac` | `0x41e4` | **`+0x338`** |
| `__DATA.__objc_const` | `0x6518` | `0x67f8` | **`+0x2e0`** |
| `__TEXT.__objc_stubs` | `0x9340` | `0x9580` | **`+0x240`** |
| `__TEXT.__objc_methlist` | `0x3a24` | `0x3c0c` | **`+0x1e8`** |
| `__TEXT.__oslogstring` | `0x14e7` | `0x1687` | **`+0x1a0`** |
| `__DATA_CONST.__const` | `0x1638` | `0x1750` | **`+0x118`** |
| `__TEXT.__objc_methtype` | `0x2535` | `0x2605` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x1568` | `0x1630` | **`+0xc8`** |
| `__DATA.__objc_data` | `0xe90` | `0xf30` | **`+0xa0`** |
| `__DATA.__objc_selrefs` | `0x29d0` | `0x2a70` | **`+0xa0`** |
| `__TEXT.__objc_classname` | `0x6af` | `0x70f` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x2b0` | `0x2cc` | **`+0x1c`** |
| `__DATA_CONST.__objc_classlist` | `0x168` | `0x178` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x100` | `0x110` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x1770` | `0x1780` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0xbc8` | `0xbd0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4a0` | `0x4a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1680.40.8.0.1
+1680.40.14.0.0

-  Functions: 1615
-  Symbols:   544
-  CStrings:  4008
+  Functions: 1661
+  Symbols:   545
+  CStrings:  4081
Symbols:
+ _MIAppReplacementStatusExpectsSourceAppIdentity
CStrings:
+ "\"%@\" has the \"%@\" entitlement, which names the app's own application identifier \"%@\". An app can only supersede a different app."
+ "%@ is a potential candidate for app replacement; prohibiting its launch"
+ "%s: Encountered unexpected LS operation of class %@ for bundle ID %@ before set app replacement source operation"
+ "%s: Encountered unexpected LS operation of class %@ for bundle ID %@ before set installation hold operation"
+ "%s: Failed to restart set app replacement source operation for %@ -> %@ : %@"
+ "%s: Failed to restart set installation hold operation for %@/%c : %@"
+ "%s: Failed to restart set persona operation for %@/%@ : %@"
+ "-[MIClientConnection endAppReplacementWithStatus:forApp:completion:]"
+ "-[MIClientConnection pushReplacementInfoForApp:replacingApp:withCompletion:]"
+ "-[MIInstallableBundle _setAppLaunchProhibitionWithReplacementRuledOut:error:]"
+ "-[MIInstallableBundle _setAppReplacementStateRulingOutReplacement:error:]"
+ "-[MILaunchServicesOperationManager _onQueue_setAppReplacementSourceBundleID:forBundleID:inDomain:error:]"
+ "-[MILaunchServicesOperationManager _onQueue_setInstallationHold:forBundleID:inDomain:error:]"
+ "-[MILaunchServicesSetAppReplacementSourceOperation initWithCoder:]"
+ "-[MILaunchServicesSetInstallationHoldOperation initWithCoder:]"
+ "<%@: %@:%lu %@/%@/%@>"
+ "<%@: %@:%lu %@/%@/%c>"
+ "@52@0:8@16Q24B32@36Q44"
+ "@56@0:8@16@24Q32@40Q48"
+ "An app cannot replace itself in a request to push app replacement info for %@"
+ "App identity was nil or the wrong type for request to end app replacement"
+ "B36@0:8B16@20^@28"
+ "B44@0:8B16@20Q28^@36"
+ "Cannot end the app replacement of %@ with %@"
+ "Cannot end the app replacement of %@ with %@, which names an app being replaced"
+ "Destination app identity was nil or the wrong type for request to push app replacement info"
+ "Encountered unexpected LS operation of class %@ for bundle ID %@ before set app replacement source operation"
+ "Encountered unexpected LS operation of class %@ for bundle ID %@ before set installation hold operation"
+ "End of app replacement with status %@ requested by client %@ for %@"
+ "Failed to restart set app replacement source operation for %@ -> %@ : %@"
+ "Failed to restart set installation hold operation for %@/%c : %@"
+ "Failed to restart set persona operation for %@/%@ : %@"
+ "Failed to tell LaunchServices about the installation holds left by the failed replacement of %@ by %@ : %@"
+ "Invalid installation domain value when deserializing app replacement source for %@: %lu"
+ "Invalid installation domain value when deserializing installation hold for %@: %lu"
+ "MILaunchServicesSetAppReplacementSourceOperation"
+ "MILaunchServicesSetInstallationHoldOperation"
+ "Missing bundle ID when deserializing installation hold"
+ "Missing destination bundle ID when deserializing app replacement source operation"
+ "Missing source bundle ID when deserializing app replacement source operation"
+ "Push of app replacement info requested by client %@ for %@ replacing %@"
+ "Source app identity was nil or the wrong type for request to push app replacement info for %@"
+ "T@\"NSDictionary\",C,N,V_pendingInstallationHoldsByBundleID"
+ "T@\"NSString\",R,N,V_destinationBundleID"
+ "T@\"NSString\",R,N,V_sourceBundleID"
+ "TB,R,N,V_installationHold"
+ "The app extension at \"%@\" has the \"%@\" entitlement, which names the app extension's own application identifier \"%@\". An app extension can only supersede a different app extension."
+ "_destinationBundleID"
+ "_installationHold"
+ "_launchServicesOperationManagerInstance"
+ "_onQueue_setAppReplacementSourceBundleID:forBundleID:inDomain:error:"
+ "_onQueue_setInstallationHold:forBundleID:inDomain:error:"
+ "_pendingInstallationHoldsByBundleID"
+ "_setAppLaunchProhibitionWithReplacementRuledOut:error:"
+ "_setAppReplacementStateRulingOutReplacement:error:"
+ "_setInstallationHold:forBundleID:error:"
+ "_sourceBundleID"
+ "applyInstallationHoldsWithError:"
+ "destinationBundleID"
+ "endAppReplacementWithStatus:forApp:completion:"
+ "getAppLaunchProhibition:withError:"
+ "initWithBundleID:domain:installationHold:registrationUUID:serialNumber:"
+ "initWithSourceBundleID:destinationBundleID:domain:registrationUUID:serialNumber:"
+ "installationHold"
+ "pendingInstallationHoldsByBundleID"
+ "pushReplacementInfoForApp:replacingApp:withCompletion:"
+ "setAppReplacementSourceBundleID:forBundleID:inDomain:error:"
+ "setAppReplacementSourceBundleIdentifier:forApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:"
+ "setInstallationHold:forBundleID:inDomain:error:"
+ "setInstallationHoldActive:onApplicationWithBundleIdentifier:operationUUID:requestContext:saveObserver:error:"
+ "setPendingInstallationHoldsByBundleID:"
+ "sourceBundleID"
+ "v40@0:8@\"MIAppIdentity\"16@\"MIAppIdentity\"24@?<v@?@\"NSError\">32"
+ "v40@0:8Q16@\"MIAppIdentity\"24@?<v@?@\"NSError\">32"
+ "v40@0:8Q16@24@?32"
- "-[MIInstallableBundle _setAppReplacementStateWithError:]"
- "_setAppReplacementStateWithError:"
```
