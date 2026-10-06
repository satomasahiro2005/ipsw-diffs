## nfcd

> `/usr/libexec/nfcd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1e5bf4` | `0x1e677c` | **`+0xb88`** |
| `__DATA_CONST.__cfstring` | `0x11760` | `0x112a0` | **`-0x4c0`** |
| `__DATA.__objc_const` | `0x14bd8` | `0x14e48` | **`+0x270`** |
| `__TEXT.__oslogstring` | `0x2016b` | `0x2038d` | **`+0x222`** |
| `__DATA_CONST.__got` | `0x838` | `0x9f8` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x2287e` | `0x226d3` | **`-0x1ab`** |
| `__TEXT.__objc_stubs` | `0xdde0` | `0xdf20` | **`+0x140`** |
| `__DATA.__objc_data` | `0x3e80` | `0x3f20` | **`+0xa0`** |
| `__TEXT.__objc_methlist` | `0x9cd4` | `0x9d6c` | **`+0x98`** |
| `__TEXT.__const` | `0x13bc` | `0x144c` | **`+0x90`** |
| `__TEXT.__objc_methname` | `0x157d0` | `0x1585d` | **`+0x8d`** |
| `__TEXT.__auth_stubs` | `0x1820` | `0x1860` | **`+0x40`** |
| `__DATA_CONST.__objc_intobj` | `0x7bc0` | `0x7bf0` | **`+0x30`** |
| `__DATA.__objc_ivar` | `0x1104` | `0x112c` | **`+0x28`** |
| `__TEXT.__objc_classname` | `0x1d22` | `0x1d44` | **`+0x22`** |
| `__DATA.__bss` | `0x2a0` | `0x2c0` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0xcb8` | `0xcd8` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x2c30` | `0x2c50` | **`+0x20`** |
| `__TEXT.__objc_methtype` | `0x4de2` | `0x4dfe` | **`+0x1c`** |
| `__DATA.__objc_selrefs` | `0x4b78` | `0x4b60` | **`-0x18`** |
| `__DATA_CONST.__const` | `0x9a18` | `0x9a00` | **`-0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x640` | `0x650` | **`+0x10`** |
| `__DATA_CONST.__objc_superrefs` | `0x470` | `0x480` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`

### Other Changes

```diff

-370.37.0.0.0
+370.38.2.0.0

+  - /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime

-  Functions: 4257
-  Symbols:   666
-  CStrings:  11378
+  Functions: 4269
+  Symbols:   669
+  CStrings:  11365
Symbols:
+ _CFAbsoluteTimeGetCurrent
+ _NSSystemClockDidChangeNotification
+ _TMGetReferenceTime
+ _TMIsAutomaticTimeEnabled
+ _mach_timebase_info
- _OBJC_CLASS_$_LSApplicationRecord
- _OBJC_CLASS_$_NSAssertionHandler
CStrings:
+ "%{public}s:%i Cannot add receipt for %{public}@/%{public}@"
+ "%{public}s:%i Could not get reference time"
+ "%{public}s:%i Failed to start wired mode to validate key %{public}@ on applet %{public}@"
+ "%{public}s:%i Fetched reference time interval: %.3f, user delta: %.3f, uncertainty: %.3f"
+ "%{public}s:%i Invalid key identifier format: %{public}@"
+ "%{public}s:%i Key %{public}@ not provisioned on applet %{public}@ - rejecting early (err=%{public}@)"
+ "%{public}s:%i Untrusted time source, need to query server"
+ "%{public}s:%i pause=%{public}d, suspendFD=%{public}d, fdSuspended=%{public}d"
+ "-[NFPaymentTagReaderDeveloperPresentmentLogger checkAvailabilityForBundleID:teamID:completion:]"
+ "-[NFPaymentTagReaderDeveloperPresentmentReporter _getFirstReportForBundleID:teamID:olderThanTimestampDay:]"
+ "-[NFPaymentTagReaderDeveloperPresentmentReporter checkLocalAvailabilityForBundleID:teamID:]"
+ "-[NFTrustedTimeSource getTime]"
+ "-[NFTrustedTimeSource handleSystemTimeChanged:]"
+ "-[_NFUnifiedAccessSession setActiveApplets:keyIdentifiers:activationConfig:]"
+ "-[_NFUnifiedAccessSession setActiveKeys:onApplet:activationConfig:]"
+ "@40@0:8@16d24Q32"
+ "Customer Factory Page"
+ "NFCD built from (B&I) Stockholm_Base-370.38.2"
+ "NFTrustedTime"
+ "NFTrustedTimeSource"
+ "Unexpected state : unknown"
+ "_cachedReferenceAbsTimeSec"
+ "_cachedReferenceMachTimeSec"
+ "_fieldDetectSuspended"
+ "_getFirstReportForBundleID:teamID:olderThanTimestampDay:"
+ "_monotonicCounterSeconds"
+ "_observerRegistered"
+ "_refreshTimeSyncSetting:"
+ "_timeSyncSettingCacheTime"
+ "_timeSyncedWithAutoTimeEnabled"
+ "_updateCachedAbsTime:machTime:"
+ "addObserver:selector:name:object:"
+ "convertMachContinuousTicksToSeconds:"
+ "d24@0:8Q16"
+ "fetchDeveloperPaymentReportsForBundleID:teamID:outError:"
+ "handleSystemTimeChanged:"
+ "initWithDate:monotonicCounterSeconds:source:"
+ "initWithTimeIntervalSinceReferenceDate:"
+ "machContinuousTimeSeconds"
+ "removeObserver:"
+ "timeIntervalSinceReferenceDate"
+ "timestampDay"
+ "v32@0:8d16d24"
- "%{public}s:%i pause=%{public}d, suspendFD=%{public}d"
- "-[NFPaymentTagReaderDeveloperPresentmentReporter _checkLocalAvailabilityForBundleID:teamID:]"
- "Empty dictionary"
- "Expects card type to *not* be NFCardTypeNone"
- "Failed to initialize nonce"
- "I32@0:8@16@24"
- "Invalid"
- "Invalid argument"
- "Invalid parameter not satisfying: %@"
- "Missing task ref"
- "NFApplet.m"
- "NFCD built from (B&I) Stockholm_Base-370.37"
- "NFDriverWrapper+Fury.m"
- "NFDriverWrapper+RFConfig.m"
- "NFDriverWrapper+SE.m"
- "NFDriverWrapper.m"
- "NFFieldNotification.m"
- "NFLoyaltyAgent.m"
- "NFReaderRestrictor.m"
- "NFRoutingConfig.m"
- "NFSecureElementHandle.m"
- "NFSecureElementWrapper+ContactlessRegistry.m"
- "NFWalletPresentationEntitlement.m"
- "Not implemented"
- "Polling mask invalid"
- "Session over released"
- "Tag Discovery cannot be empty"
- "Tag not handle!"
- "Unexpected class"
- "Unexpected config: %@"
- "Unexpected state %u"
- "_NFContactlessSession.m"
- "_NFReaderSession+Entitlement.m"
- "_NFSecureTransactionServicesHandoverHybridSession.m"
- "_NFSecureTransactionServicesHandoverSession.m"
- "_appletCollection!=nil"
- "_checkLocalAvailabilityForBundleID:teamID:"
- "_driver != nil"
- "_handleOseSelect:"
- "clearMultiTagPollingState"
- "closeSession:"
- "configureMultiTagPolling"
- "crs_authorizeForECommerce:cryptogram:encryptedPIN:request:response:"
- "currentHandler"
- "driver not open"
- "driver session not held"
- "embeddedCardEmulationWithHCE:emulationType:"
- "embeddedExpressCardEmulation:"
- "entitlementFromXPC:"
- "getControllerInfo:"
- "getRFSettings:"
- "getSecureElementInfo:info:"
- "handleFailureInMethod:object:file:lineNumber:description:"
- "setPollingMask:tagConfig:"
- "setSecureElement:alwaysOn:"
- "theResponse != nil"
```
