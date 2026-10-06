## libcoreroutine.dylib

> `/usr/lib/libcoreroutine.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6a9fd8` | `0x6b003c` | **`+0x6064`** |
| `__TEXT.__oslogstring` | `0x87e0c` | `0x88b9d` | **`+0xd91`** |
| `__TEXT.__gcc_except_tab` | `0x2e2b0` | `0x2e9a8` | **`+0x6f8`** |
| `__TEXT.__cstring` | `0x49c9f` | `0x4a0f0` | **`+0x451`** |
| `__AUTH_CONST.__cfstring` | `0x2b380` | `0x2b460` | **`+0xe0`** |
| `__TEXT.__unwind_info` | `0xf060` | `0xf118` | **`+0xb8`** |
| `__DATA_DIRTY.__objc_data` | `0xc030` | `0xbf90` | **`-0xa0`** |
| `__AUTH_CONST.__objc_const` | `0x56258` | `0x561c0` | **`-0x98`** |
| `__DATA_CONST.__objc_selrefs` | `0x1b178` | `0x1b210` | **`+0x98`** |
| `__AUTH_CONST.__const` | `0x3638` | `0x36b8` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x348c8` | `0x34940` | **`+0x78`** |
| `__AUTH.__objc_data` | `0x2200` | `0x2250` | **`+0x50`** |
| `__DATA_CONST.__const` | `0x104c8` | `0x10508` | **`+0x40`** |
| `__DATA_CONST.__got` | `0x3500` | `0x34d0` | **`-0x30`** |
| `__DATA_CONST.__objc_superrefs` | `0x1278` | `0x1268` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x12e8` | `0x12f0` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x1680` | `0x1678` | **`-0x8`** |
| `__TEXT.__eh_frame` | `0x6e0` | `0x6d8` | **`-0x8`** |
| `__DATA_DIRTY.__objc_ivar` | `0x126c` | `0x1270` | **`+0x4`** |

### Other Changes

```diff

-1109.0.3.0.0
+1114.0.0.0.0

-  Functions: 21853
-  Symbols:   33752
-  CStrings:  16164
+  Functions: 21891
+  Symbols:   33776
+  CStrings:  16224
Symbols:
+ +[RTAuthorizationManager coreRoutineLocationDetails]
+ +[RTAuthorizationManager readCoreRoutineLocationClientEnabled]
+ +[RTAuthorizationManager readSystemLocationServicesEnabled]
+ -[RTAssetManager copyRoutineAssetSettingsWithCompatibilityVersion:contentVersion:]
+ -[RTAuthorizationManager _postRoutineEnabledStateChange]
+ -[RTAuthorizationManager _readLocationServicesEnabled]
+ -[RTAuthorizationManager _refreshAllCachedState]
+ -[RTAuthorizationManager _refreshLocationServicesEnabled]
+ -[RTAuthorizationManager _seedCachedStateFromDefaults]
+ -[RTAuthorizationManager checkCompositeEnablement]
+ -[RTAuthorizationManager defaultsManager]
+ -[RTAuthorizationManager fetchLocationServicesEnabledWithHandler:]
+ -[RTAuthorizationManager handleAuthorizationResetNotification]
+ -[RTAuthorizationManager handleLocationServicesChangedNotification]
+ -[RTAuthorizationManager initWithPlatform:userSessionMonitor:defaultsManager:]
+ -[RTAuthorizationManager setCoreRoutineEnabled:]
+ -[RTAuthorizationManager setLocationServicesEnabled:]
+ -[RTAuthorizationManagerNotificationLocationServicesEnabled enabled]
+ -[RTAuthorizationManagerNotificationLocationServicesEnabled initWithEnabled:]
+ -[RTAuthorizationManagerNotificationLocationServicesEnabled init]
+ -[RTAuthorizationManagerNotificationRoutineEnabled init]
+ -[RTAuthorizedLocationZDRLocationManager _isLocationServiceEnabled]
+ -[RTAuthorizedLocationZDRLocationManager authorizationManager]
+ -[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:authorizationManager:]
+ -[RTBluePOIMonitor shouldPostMeaningfulChangeOnPOIEstimate:fromPOIEstimate:]
+ -[RTElevationProvider authorizationManager]
+ -[RTElevationProvider initWithAltimeter:authorizationManager:]
+ -[RTElevationProvider initWithAuthorizationManager:]
+ -[RTElevationProvider setAuthorizationManager:]
+ -[RTPlaceInferenceManager _filterStaleAccessPoints:referenceLocation:]
+ -[RTTripClusterProcessor cleanUpOrphanedLocalStoreEntries:]
+ -[RTTripClusterProcessorOptions cleanUpOrphanedLocalStoreEntries]
+ -[RTTripClusterProcessorOptions setCleanUpOrphanedLocalStoreEntries:]
+ -[RTTripClusterRoadTransitionsDataStore _getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRoadTransitionsDataStore getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRoadTransitionsDataStore getAllStoredClusterIDs]
+ -[RTTripClusterRouteStore _getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRouteStore getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRouteStore getAllStoredClusterIDs]
+ -[RTTripClusterRouteSummaryStore _getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRouteSummaryStore getAllStoredClusterIDsWithHandler:]
+ -[RTTripClusterRouteSummaryStore getAllStoredClusterIDs]
+ GCC_except_table97
+ _CFEqual
+ _CLAuthorizationStatusChangedNotification
+ _OBJC_CLASS_$_RTAuthorizationManagerNotificationLocationServicesEnabled
+ _OBJC_IVAR_$_RTAuthorizationManagerNotificationLocationServicesEnabled._enabled
+ _OBJC_IVAR_$_RTAuthorizedLocationZDRLocationManager._authorizationManager
+ _OBJC_IVAR_$_RTElevationProvider._authorizationManager
+ _OBJC_IVAR_$_RTTripClusterProcessorOptions._cleanUpOrphanedLocalStoreEntries
+ _OBJC_METACLASS_$_RTAuthorizationManagerNotificationLocationServicesEnabled
+ __OBJC_$_INSTANCE_METHODS_RTAuthorizationManagerNotificationLocationServicesEnabled
+ __OBJC_$_INSTANCE_VARIABLES_RTAuthorizationManagerNotificationLocationServicesEnabled
+ __OBJC_$_PROP_LIST_RTAuthorizationManagerNotificationLocationServicesEnabled
+ __OBJC_CLASS_RO_$_RTAuthorizationManagerNotificationLocationServicesEnabled
+ __OBJC_METACLASS_RO_$_RTAuthorizationManagerNotificationLocationServicesEnabled
+ ___227-[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:authorizationManager:]_block_invoke
+ ___38-[RTElevationProvider _setupAltimeter]_block_invoke
+ ___49-[RTTripClusterRouteStore getAllStoredClusterIDs]_block_invoke
+ ___52-[RTElevationProvider initWithAuthorizationManager:]_block_invoke
+ ___56-[RTAuthorizedLocationManager _isLocationServiceEnabled]_block_invoke
+ ___56-[RTTripClusterRouteSummaryStore getAllStoredClusterIDs]_block_invoke
+ ___61-[RTTripClusterRouteStore getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___62-[RTAuthorizationManager handleAuthorizationResetNotification]_block_invoke
+ ___62-[RTTripClusterRouteStore _getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___62-[RTTripClusterRouteStore _getAllStoredClusterIDsWithHandler:]_block_invoke_2
+ ___63-[RTTripClusterRoadTransitionsDataStore getAllStoredClusterIDs]_block_invoke
+ ___66-[RTAuthorizationManager fetchLocationServicesEnabledWithHandler:]_block_invoke
+ ___67-[RTAuthorizationManager handleLocationServicesChangedNotification]_block_invoke
+ ___67-[RTAuthorizedLocationZDRLocationManager _isLocationServiceEnabled]_block_invoke
+ ___68-[RTTripClusterRouteSummaryStore getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___69-[RTTripClusterRouteSummaryStore _getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___69-[RTTripClusterRouteSummaryStore _getAllStoredClusterIDsWithHandler:]_block_invoke_2
+ ___70-[RTPlaceInferenceManager _filterStaleAccessPoints:referenceLocation:]_block_invoke
+ ___70-[RTPlaceInferenceManager _filterStaleAccessPoints:referenceLocation:]_block_invoke_2
+ ___70-[RTPlaceInferenceManager _filterStaleAccessPoints:referenceLocation:]_block_invoke_3
+ ___72-[RTLocationAwarenessManager(metric) considerUpdateActiveRequestMetrics]_block_invoke_6
+ ___75-[RTTripClusterRoadTransitionsDataStore getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___76-[RTBluePOIMonitor shouldPostMeaningfulChangeOnPOIEstimate:fromPOIEstimate:]_block_invoke
+ ___76-[RTBluePOIMonitor shouldPostMeaningfulChangeOnPOIEstimate:fromPOIEstimate:]_block_invoke_2
+ ___76-[RTTripClusterRoadTransitionsDataStore _getAllStoredClusterIDsWithHandler:]_block_invoke
+ ___76-[RTTripClusterRoadTransitionsDataStore _getAllStoredClusterIDsWithHandler:]_block_invoke_2
+ ___79+[SMInitiatorEligibility checkLocationServicesEnabledWithAuthorizationManager:]_block_invoke
+ ___block_descriptor_120_e8_32s40s48s56s64s72s80s88s96s104s112s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8s112l8
+ ___block_descriptor_32_e27_B24?0"NSURL"8"NSError"16l
+ ___block_descriptor_32_e71_q24?0"CLLocationExtendedTimestamps"8"CLLocationExtendedTimestamps"16l
+ ___block_descriptor_40_e8_32s_e31_q24?0"NSNumber"8"NSNumber"16ls32l8
+ ___block_descriptor_88_e8_32s40s48s56bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8
+ _onCachedStateInvalidatingNotification
- +[RTAuthorizationManager allocWithZone:]
- +[RTPeopleDiscoveryAdvertisement supportsSecureCoding]
- -[RTAuthorizationManager dispatcher]
- -[RTAuthorizationManager handleAppResetChangeNotification]
- -[RTAuthorizationManager initWithPlatform:userSessionMonitor:]
- -[RTAuthorizationManager isReady]
- -[RTAuthorizationManager setDispatcher:]
- -[RTAuthorizationManager setPlatform:]
- -[RTAuthorizationManager setReady:]
- -[RTAuthorizationManager setUserSessionMonitor:]
- -[RTAuthorizationManager setup]
- -[RTAuthorizationManager_Embedded initWithMetricManager:platform:userSessionMonitor:]
- -[RTAuthorizationManager_Embedded isLocationServicesEnabled]
- -[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:]
- -[RTElevationProvider initWithAltimeter:]
- -[RTElevationProvider init]
- -[RTPeopleDiscoveryAdvertisement .cxx_destruct]
- -[RTPeopleDiscoveryAdvertisement address]
- -[RTPeopleDiscoveryAdvertisement contactID]
- -[RTPeopleDiscoveryAdvertisement copyWithZone:]
- -[RTPeopleDiscoveryAdvertisement descriptionDictionary]
- -[RTPeopleDiscoveryAdvertisement description]
- -[RTPeopleDiscoveryAdvertisement encodeWithCoder:]
- -[RTPeopleDiscoveryAdvertisement hash]
- -[RTPeopleDiscoveryAdvertisement initWithAddress:rssi:scanDate:contactID:]
- -[RTPeopleDiscoveryAdvertisement initWithCoder:]
- -[RTPeopleDiscoveryAdvertisement init]
- -[RTPeopleDiscoveryAdvertisement isEqual:]
- -[RTPeopleDiscoveryAdvertisement rssi]
- -[RTPeopleDiscoveryAdvertisement scanDate]
- GCC_except_table64
- GCC_except_table86
- _OBJC_CLASS_$_RTAuthorizationManager_Embedded
- _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._address
- _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._contactID
- _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._rssi
- _OBJC_IVAR_$_RTPeopleDiscoveryAdvertisement._scanDate
- _OBJC_METACLASS_$_RTAuthorizationManager_Embedded
- _OBJC_METACLASS_$_RTPeopleDiscoveryAdvertisement
- __OBJC_$_CLASS_METHODS_RTPeopleDiscoveryAdvertisement
- __OBJC_$_CLASS_PROP_LIST_RTPeopleDiscoveryAdvertisement
- __OBJC_$_INSTANCE_METHODS_RTAuthorizationManager_Embedded
- __OBJC_$_INSTANCE_METHODS_RTPeopleDiscoveryAdvertisement
- __OBJC_$_INSTANCE_VARIABLES_RTPeopleDiscoveryAdvertisement
- __OBJC_$_PROP_LIST_RTPeopleDiscoveryAdvertisement
- __OBJC_CLASS_PROTOCOLS_$_RTPeopleDiscoveryAdvertisement
- __OBJC_CLASS_RO_$_RTAuthorizationManager_Embedded
- __OBJC_CLASS_RO_$_RTPeopleDiscoveryAdvertisement
- __OBJC_METACLASS_RO_$_RTAuthorizationManager_Embedded
- __OBJC_METACLASS_RO_$_RTPeopleDiscoveryAdvertisement
- ___206-[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:]_block_invoke
- ___27-[RTElevationProvider init]_block_invoke
- ___31-[RTAuthorizationManager setup]_block_invoke
- ___58-[RTAuthorizationManager handleAppResetChangeNotification]_block_invoke
- ___block_descriptor_112_e8_32s40s48s56s64s72s80s88s96s104s_e5_v8?0ls32l8s40l8s48l8s56l8s64l8s72l8s80l8s88l8s96l8s104l8
- ___block_descriptor_48_e8_32r_e17_v16?0"NSError"8lr32l8
- ___block_descriptor_88_e8_32s40s48s56s64bs_e17_v16?0"NSError"8ls32l8s40l8s48l8s56l8s64l8
- _kRTBugCaptureCategoryBackgroundTaskHighFailureRate
- _kRTBugCaptureCategoryBackgroundTaskSchedulingViolation
- _kRTBugCaptureCategoryDataIntegrityViolation
- _kRTBugCaptureCategoryExceptionCaught
- _kRTBugCaptureCategoryIpsDetected
- _kRTBugCaptureCategoryLOIUUIDStabilityIssueDetected
- _kRTBugCaptureCategoryVisitGapDetected
- _onAppResetChangedNotification
CStrings:
+ "%@ Add elevation entries: count,%{public}ld"
+ "%@ Adding large number of elevation in one chunk is not supported"
+ "%@ Elevation storeElevations timeout %@"
+ "%@ purging older than %@"
+ "%@, %@, CoreRoutine's location client enabled, %@"
+ "%@, %@, CoreRoutine, %@"
+ "%@, %@, Location Services, %@"
+ "%@, %@, Location services enabled, %@"
+ "%@, %@, cached auth state from defaults, Location Services, %@, CoreRoutine, %@, enabled, %@"
+ "%@, %@, refreshed after CLAppResetChangedNotification, enabled, %@"
+ "%@, %@, refreshed after CLAuthorizationStatusChangedNotification, Location Services, %@"
+ "%@, %@, sending placeInferences, %lu, monitor, %@, clientIdentifier, %@, includeCandidates, %@, fcm, %d"
+ "%@, %@, supported, %@, Location Services, %@, CoreRoutine, %@, enabled, %@"
+ "%@, bug capture result for reason %@ (module: %@, category: %ld) with diagnostics mask 0x%lX: %@"
+ "%@, late reverse-geocode result, %{sensitive}@, visit, %{sensitive}@"
+ "%@, no Routine asset currently loaded in CoreLocation; nothing to sync"
+ "%@, primary confidence, %f, below consider threshold, %f, no usable finer granularity item; attempting late reverse-geocode, visit, %{sensitive}@"
+ "%@, primary confidence, %f, below consider threshold, %f, promoting finer granularity item (confidence, %f) to primary, %{sensitive}@, visit, %{sensitive}@"
+ "%@, primary confidence, %f, below consider threshold, %f, revGeo already called, dropping primary, visit, %{sensitive}@"
+ "%@, primary confidence, %f, below pass-through threshold, %f, swapping primary to finer granularity item (confidence, %f), %{sensitive}@, visit, %{sensitive}@"
+ "%@,%@,Cleanup completed. Deleted %lu orphaned route entries, %lu orphaned road transition entries, and %lu orphaned route summary entries"
+ "%@,%@,Cluster fetch returned nil from one or both stores, aborting cleanup to avoid potential data loss"
+ "%@,%@,Defer orphaned local store entries cleanup"
+ "%@,%@,Error fetching all cluster IDs: %@"
+ "%@,%@,Failed to delete orphaned road transition entries for clusterID,%@"
+ "%@,%@,Failed to delete orphaned route entries for clusterID,%@"
+ "%@,%@,Failed to delete orphaned route summary entries for clusterID,%@"
+ "%@,%@,Found %lu valid cluster IDs (local: %lu, cloud: %lu)"
+ "%@,%@,No clusters found in local or cloud store, skipping cleanup"
+ "%@,%@,Orphaned local store entries cleanup process disabled by default"
+ "%@,%@,Orphaned local store entries cleanup process finished successfully"
+ "%@,%@,Processing deferred during orphaned road transition entry cleanup"
+ "%@,%@,Processing deferred during orphaned route entry cleanup"
+ "%@,%@,Processing deferred during orphaned route summary entry cleanup"
+ "%@,%@,Road transitions cluster ID fetch returned nil, skipping transitions cleanup"
+ "%@,%@,Route cluster ID fetch returned nil, skipping route orphan cleanup"
+ "%@,%@,Route summary cluster ID fetch returned nil, skipping route summary orphan cleanup"
+ "%@,%@,Semaphore timeout fetching all cluster IDs: %@"
+ "%@,%@,Starting cleanup process for orphaned local store entries"
+ "%@,%@,Successfully deleted orphaned road transition entries for clusterID,%@"
+ "%@,%@,Successfully deleted orphaned route entries for clusterID,%@"
+ "%@,%@,Successfully deleted orphaned route summary entries for clusterID,%@"
+ "%@.%@.ACAccountStore.init"
+ "%@.%@.HMHomeManager.init"
+ "%@:%@ authorizationManager is nil, leaving activeRequestLocationServiceOn as %d"
+ "%@:%@ no CoreRoutine location entity registered; cached routineEnabled=%@ locally, will reconcile on next CLAppResetChangedNotification"
+ "%@:%@ timed out waiting for cached LS state, fell back to direct CL read, locationServicesEnabled=%@, error=%{public}@"
+ "%@:%@ timed out waiting for routine-enabled state from RTAuthorizationManager, treating as disabled, error=%{public}@"
+ "-[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:authorizationManager:]"
+ "-[RTTripClusterProcessor cleanUpOrphanedLocalStoreEntries:]"
+ "-[RTTripClusterRoadTransitionsDataStore _getAllStoredClusterIDsWithHandler:]"
+ "-[RTTripClusterRoadTransitionsDataStore getAllStoredClusterIDsWithHandler:]"
+ "-[RTTripClusterRouteStore _getAllStoredClusterIDsWithHandler:]"
+ "-[RTTripClusterRouteStore getAllStoredClusterIDsWithHandler:]"
+ "-[RTTripClusterRouteSummaryStore _getAllStoredClusterIDsWithHandler:]"
+ "-[RTTripClusterRouteSummaryStore getAllStoredClusterIDsWithHandler:]"
+ "05:27:32"
+ "<%@: %p, downsampleFactor,%ld,windowSize,%ld,maxLocationPerTrip,%ld,maxProcessedTripSegments,%ld,useMaxProcessedTripSegments,%@,purgeClustersDataBase,%@,distBetweenTrips_km,%.2f,distanceThreshold_m,%.2f,unreachableDistance_m,%.2f,clusterLifeTimeThreshold_d,%ld,lengthDeviationThreshold_m,%.2f,locationThresholdRadius_m,%.2f,distAccuracyThreshold_m,%.2f,writeTripSegmentsToFile,%@,enableClusterProcessing,%@,saveToHTML,%@,clusterProcessorMode,%ld,learnedRoutesCurrentLocationSPIEnabled,%@,maxCleanUpOperationsCountPerRun,%ld,maxRouteRehydrationsCountPerRun,%ld,maxDeletionAttemptsForClusterData,%ld,rehydrateRouteLocationsFromWaypoints,%@,cleanUpClusterWithDuplicateWaypoints,%@,cleanUpOrphanedLocalStoreEntries,%@>"
+ "B24@?0@\"NSURL\"8@\"NSError\"16"
+ "Checking for routined IPS logs"
+ "CrashReporter contains more than %lu entries; stopping scan and filing radar with files collected so far"
+ "Discarding WiFi scan, AP %{sensitive}@, no location match within 5s"
+ "Discarding stale WiFi scan, AP %{sensitive}@, distance %.1fm, error %@"
+ "Error enumerating %@: %@"
+ "Found %lu routined IPS files in CrashReporter directory"
+ "FullContinuousMonitoring"
+ "IPS scan inspected %lu total entries (capReached: %d)"
+ "IPS scan resolved crashReporterPath to: %{public}@"
+ "Jun 12 2026"
+ "No CoreRoutine location entity registered with locationd; cached locally only."
+ "RTAuthorizationManagerCachedCoreRoutineClientEnabled"
+ "RTAuthorizationManagerCachedLocationServicesEnabled"
+ "RTAuthorizedLocationManager._curateAuthorizedLocations.fetchLOIHistory"
+ "RTAuthorizedLocationManager._curateAuthorizedLocations.fetchVisitLogs"
+ "RTAuthorizedLocationManager._getCurrentVisit"
+ "RTAuthorizedLocationManager._readConfirmationStatusFromDisk"
+ "RTDefaultsTripClusterCleanUpOrphanedLocalStoreEntries"
+ "Radar alert suppressed by user until global backoff period expires"
+ "Radar alert suppressed for reason: %{public}@ (user selected 'Stop Asking' - suppressed until %@)"
+ "Skipping IPS log check on customer install"
+ "Unexpected Darwin notification on cached-state observer, %@"
+ "elevation count exceeds maximum samples in one shot."
+ "encrypted data unavailable - please ensure the device is unlocked and try again."
+ "q24@?0@\"CLLocationExtendedTimestamps\"8@\"CLLocationExtendedTimestamps\"16"
+ "shouldPostMeaningfulChange called with nil newPOIEstimate — aggregator failure?"
+ "shouldPostSignificantChange called with nil newPOIEstimate — aggregator failure?"
- "%@, %@, sending placeInferences, %lu, monitor, %@, clientIdentifier, %@, includeCandidates, %@"
- "%@, Received a NULL  CFDictionaryRef routineAssetSettingsDict"
- "%@, bug capture result for reason %@ (module: %@, category: %@) with diagnostics mask 0x%lX: %@"
- "-[RTAuthorizedLocationZDRLocationManager initZDRLocationManager:visitManager:distanceCalculator:locationManager:learnedLocationManager:defaultsManager:confirmationStatus:zdrLocationsStore:platform:metrics:]"
- "-[RTHomeKitManager initWithHomeManager:]"
- "22:04:25"
- "<%@: %p, downsampleFactor,%ld,windowSize,%ld,maxLocationPerTrip,%ld,maxProcessedTripSegments,%ld,useMaxProcessedTripSegments,%@,purgeClustersDataBase,%@,distBetweenTrips_km,%.2f,distanceThreshold_m,%.2f,unreachableDistance_m,%.2f,clusterLifeTimeThreshold_d,%ld,lengthDeviationThreshold_m,%.2f,locationThresholdRadius_m,%.2f,distAccuracyThreshold_m,%.2f,writeTripSegmentsToFile,%@,enableClusterProcessing,%@,saveToHTML,%@,clusterProcessorMode,%ld,learnedRoutesCurrentLocationSPIEnabled,%@,maxCleanUpOperationsCountPerRun,%ld,maxRouteRehydrationsCountPerRun,%ld,maxDeletionAttemptsForClusterData,%ld,rehydrateRouteLocationsFromWaypoints,%@,cleanUpClusterWithDuplicateWaypoints,%@>"
- "Address"
- "CFDictionaryRef routineAssetSettingsDict from CL is NULL"
- "Checking for routined IPS logs (last check: %@)"
- "CoreRoutine's location client enabled, %@"
- "CoreRoutine's services supported, %@"
- "Found %lu routined IPS files in CrashReporter directory (filtered by last check: %@)"
- "Including IPS file: %@ (modified: %@, last check: %@)"
- "Invalid parameter not satisfying: category"
- "Invalid parameter not satisfying: homeManager (in %s:%d)"
- "LastIpsCheckCompletedDate"
- "Marked IPS check completed at: %@"
- "May 29 2026"
- "N/A (first run)"
- "Overall CoreRoutine services enabled after app reset changed notification, %@"
- "Radar alert suppressed by user until 30-day period expires"
- "Radar alert suppressed for reason: %{public}@ (user selected 'Stop Asking for 30 days' - suppressed until %@)"
- "Skipping IPS file: %@ (modified: %@, before last check: %@)"
- "Unable to get attributes for IPS file at path: %@, error: %@"
- "encrypetd data unavailable - please ensure the device is unlocked and try again."
```
