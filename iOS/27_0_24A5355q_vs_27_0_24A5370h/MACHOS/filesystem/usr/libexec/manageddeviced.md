## manageddeviced

> `/usr/libexec/manageddeviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x42d14` | `0x414d4` | **`-0x1840`** |
| `__TEXT.__objc_methname` | `0xa475` | `0x9ce5` | **`-0x790`** |
| `__DATA.__objc_const` | `0x8d18` | `0x8768` | **`-0x5b0`** |
| `__TEXT.__objc_stubs` | `0x90e0` | `0x8d60` | **`-0x380`** |
| `__TEXT.__objc_methtype` | `0x10f4` | `0xdc1` | **`-0x333`** |
| `__TEXT.__oslogstring` | `0x665c` | `0x63d8` | **`-0x284`** |
| `__TEXT.__objc_methlist` | `0x41bc` | `0x3fbc` | **`-0x200`** |
| `__DATA.__objc_selrefs` | `0x2a58` | `0x28c0` | **`-0x198`** |
| `__TEXT.__cstring` | `0x3040` | `0x2f5e` | **`-0xe2`** |
| `__DATA_CONST.__cfstring` | `0x3560` | `0x3480` | **`-0xe0`** |
| `__TEXT.__gcc_except_tab` | `0x73c` | `0x6ac` | **`-0x90`** |
| `__DATA_CONST.__const` | `0x19d8` | `0x1960` | **`-0x78`** |
| `__DATA.__data` | `0x4e0` | `0x480` | **`-0x60`** |
| `__DATA_CONST.__got` | `0x960` | `0x908` | **`-0x58`** |
| `__TEXT.__unwind_info` | `0x1270` | `0x1218` | **`-0x58`** |
| `__DATA.__objc_data` | `0x21c0` | `0x2170` | **`-0x50`** |
| `__TEXT.__auth_stubs` | `0xd10` | `0xcc0` | **`-0x50`** |
| `__TEXT.__objc_classname` | `0xd98` | `0xd61` | **`-0x37`** |
| `__DATA_CONST.__auth_got` | `0x698` | `0x670` | **`-0x28`** |
| `__DATA.__bss` | `0x358` | `0x338` | **`-0x20`** |
| `__DATA.__objc_ivar` | `0x1fc` | `0x1e8` | **`-0x14`** |
| `__DATA_CONST.__objc_classlist` | `0x360` | `0x358` | **`-0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x68` | `0x60` | **`-0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x2f8` | `0x2f0` | **`-0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`

### Other Changes

```diff

-20.0.0.0.0
+22.0.0.0.0

-  - /System/Library/Frameworks/_LocationEssentials.framework/_LocationEssentials

-  Functions: 1732
-  Symbols:   533
-  CStrings:  2772
+  Functions: 1696
+  Symbols:   517
+  CStrings:  2675
Symbols:
- _NSCocoaErrorDomain
- _NSFileProtectionKey
- _NSFileProtectionNone
- _OBJC_CLASS_$_CLEmergencyEnablementAssertion
- _OBJC_CLASS_$_CLLocationManager
- _OBJC_CLASS_$_NSDateFormatter
- _OBJC_CLASS_$_NSFileCoordinator
- _OBJC_CLASS_$_NSLocale
- __dispatch_source_type_timer
- _dispatch_assert_queue$V2
- _dispatch_queue_attr_make_with_autorelease_frequency
- _dispatch_queue_attr_make_with_qos_class
- _dispatch_source_cancel
- _dispatch_source_set_timer
- _kCLLocationAccuracyBest
- _kMCMDMLostModeLastLocationRequestDateKey
CStrings:
- "@\"CLLocationManager\""
- "@\"NSObject<OS_dispatch_source>\""
- "B24@0:8@\"CLLocationManager\"16"
- "CLLocationManagerDelegate"
- "Could not read device last located time interval for update: %@"
- "Could not read device last located time interval: %@"
- "Could not read device last location requested file: %@"
- "Could not remove device last located file: %@"
- "Could not write device last located time interval"
- "Could not write device last located time interval URL resourve values: %@"
- "DMDLDLMServiceQueue"
- "Device last located on %{public}@. Creating localized message."
- "Location Manager failed: error=%{public}@"
- "Location Manager returned a location, but we can't report it because we can't record that fact. Throwing location information away."
- "Location Manager returned a location."
- "Location Manager timed out"
- "LostModeRequest.plist"
- "MDDLostDeviceLocationManager"
- "MDDLostDeviceLocationManager getCurrentLocationForOriginator:completion:"
- "T@\"CLLocationManager\",&,N,V_locationManager"
- "T@\"MDDLostDeviceLocationManager\",R,N"
- "T@\"NSObject<OS_dispatch_source>\",&,N,V_timeoutTimerDispatchSource"
- "T@\"NSString\",C,N,V_originator"
- "The location of this device was sent to %@ at %@ on %@."
- "_cleanupAfterResponseFromLocationManagerOrTimeout"
- "_locationManager"
- "_originator"
- "_timeoutTimerDispatchSource"
- "_updateLostModeFileForOriginator:"
- "clearLastLocationRequestedDate"
- "coordinateReadingItemAtURL:options:error:byAccessor:"
- "coordinateWritingItemAtURL:options:error:byAccessor:"
- "currentLocale"
- "dateWithTimeIntervalSinceReferenceDate:"
- "dictionaryWithContentsOfURL:"
- "doubleValue"
- "getCurrentLocationForOriginator:completion:"
- "initWithEffectiveBundle:delegate:onQueue:"
- "lastLocationRequestedDateMessage"
- "lastObject"
- "locationManager"
- "locationManager:didChangeAuthorizationStatus:"
- "locationManager:didDetermineState:forRegion:"
- "locationManager:didEnterRegion:"
- "locationManager:didExitRegion:"
- "locationManager:didFailRangingBeaconsForConstraint:error:"
- "locationManager:didFailWithError:"
- "locationManager:didFinishDeferredUpdatesWithError:"
- "locationManager:didRangeBeacons:inRegion:"
- "locationManager:didRangeBeacons:satisfyingConstraint:"
- "locationManager:didStartMonitoringForRegion:"
- "locationManager:didUpdateHeading:"
- "locationManager:didUpdateLocations:"
- "locationManager:didUpdateToLocation:fromLocation:"
- "locationManager:didVisit:"
- "locationManager:monitoringDidFailForRegion:withError:"
- "locationManager:rangingBeaconsDidFailForRegion:withError:"
- "locationManagerDidChangeAuthorization:"
- "locationManagerDidPauseLocationUpdates:"
- "locationManagerDidResumeLocationUpdates:"
- "locationManagerShouldDisplayHeadingCalibration:"
- "newAssertionForBundle:withReason:"
- "organizationName"
- "removeItemAtURL:error:"
- "requestLocation"
- "serverName"
- "setAuthorizationStatusByType:forBundle:"
- "setDateStyle:"
- "setDesiredAccuracy:"
- "setLocale:"
- "setLocationManager:"
- "setOriginator:"
- "setResourceValues:error:"
- "setTimeStyle:"
- "setTimeoutTimerDispatchSource:"
- "stopUpdatingLocation"
- "stringFromDate:"
- "systemLostModeRequestPath"
- "timeoutTimerDispatchSource"
- "v16@?0@\"NSURL\"8"
- "v24@0:8@\"CLLocationManager\"16"
- "v28@0:8@\"CLLocationManager\"16i24"
- "v28@0:8@16i24"
- "v32@0:8@\"CLLocationManager\"16@\"CLHeading\"24"
- "v32@0:8@\"CLLocationManager\"16@\"CLRegion\"24"
- "v32@0:8@\"CLLocationManager\"16@\"CLVisit\"24"
- "v32@0:8@\"CLLocationManager\"16@\"NSArray\"24"
- "v32@0:8@\"CLLocationManager\"16@\"NSError\"24"
- "v40@0:8@\"CLLocationManager\"16@\"CLBeaconIdentityConstraint\"24@\"NSError\"32"
- "v40@0:8@\"CLLocationManager\"16@\"CLBeaconRegion\"24@\"NSError\"32"
- "v40@0:8@\"CLLocationManager\"16@\"CLLocation\"24@\"CLLocation\"32"
- "v40@0:8@\"CLLocationManager\"16@\"CLRegion\"24@\"NSError\"32"
- "v40@0:8@\"CLLocationManager\"16@\"NSArray\"24@\"CLBeaconIdentityConstraint\"32"
- "v40@0:8@\"CLLocationManager\"16@\"NSArray\"24@\"CLBeaconRegion\"32"
- "v40@0:8@\"CLLocationManager\"16q24@\"CLRegion\"32"
- "v40@0:8@16q24@32"
- "writeToURL:atomically:"
```
