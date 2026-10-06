## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x19b298` | `0x19bd3c` | **`+0xaa4`** |
| `__TEXT.__oslogstring` | `0x13897` | `0x13c27` | **`+0x390`** |
| `__AUTH_CONST.__objc_const` | `0x2aa48` | `0x2ac80` | **`+0x238`** |
| `__TEXT.__objc_methlist` | `0x1b300` | `0x1b458` | **`+0x158`** |
| `__DATA_CONST.__objc_selrefs` | `0xb5e0` | `0xb690` | **`+0xb0`** |
| `__DATA.__data` | `0x3c38` | `0x3c98` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x6c80` | `0x6cc8` | **`+0x48`** |
| `__TEXT.__gcc_except_tab` | `0x1788` | `0x17c8` | **`+0x40`** |
| `__AUTH_CONST.__objc_intobj` | `0x540` | `0x558` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x18dc` | `0x18f4` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0x1500` | `0x1508` | **`+0x8`** |
| `__DATA_CONST.__objc_catlist` | `0xb8` | `0xc0` | **`+0x8`** |
| `__DATA_CONST.__objc_protolist` | `0x408` | `0x410` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-1616.100.2.2.1
+1620.100.1.2.3

-  Functions: 11471
-  Symbols:   15920
-  CStrings:  4563
+  Functions: 11497
+  Symbols:   15965
+  CStrings:  4571
Symbols:
+ +[TUCallCapabilities canEnableThumperCalling]
+ +[TUCallHistoryController callHistoryControllerWithCoalescingStrategy:options:shouldUpdateMetadataCache:recentsDataSource:]
+ -[TUCallCenter isGreenTea]
+ -[TUCallCenter registerClientSupportsExtendedSuspensionState:]
+ -[TUCallHistoryController initWithCoalescingStrategy:options:dataSource:recentsDataSource:shouldUpdateMetadataCache:]
+ -[TUCallHistoryController isPerformingRecentCallsRefresh]
+ -[TUCallHistoryController performRecentCallsRefresh]
+ -[TUCallHistoryController recentCallsRefreshRequestedDuringFetch]
+ -[TUCallHistoryController recentsDataSource]
+ -[TUCallHistoryController requestRecentCallsRefresh]
+ -[TUCallHistoryController setIsPerformingRecentCallsRefresh:]
+ -[TUCallHistoryController setRecentCallsRefreshRequestedDuringFetch:]
+ -[TUCallHistoryController setRecentsDataSource:]
+ -[TUCallServicesInterface _shouldTearDownXPCConnectionForConnectionRequestWithNotifyStatus:daemonLaunchTime:]
+ -[TUCallServicesInterface clientSupportsExtendedSuspensionState]
+ -[TUCallServicesInterface lastOutgoingXPCMessageTime]
+ -[TUCallServicesInterface pickRouteWithUniqueIdentifier:shouldWaitUntilAvailable:routeSelectionProvenance:forRouteController:]
+ -[TUCallServicesInterface setClientSupportsExtendedSuspensionState:]
+ -[TUCallServicesInterface setLastOutgoingXPCMessageTime:]
+ -[TUCallServicesInterface stampLastOutgoingXPCMessageTime]
+ -[TURouteController pickRoute:routeSelectionProvenance:]
+ -[TURouteController pickRouteWhenAvailableWithUniqueIdentifier:routeSelectionProvenance:]
+ -[TURouteController pickRouteWithUniqueIdentifier:routeSelectionProvenance:]
+ -[TUSenderIdentityCapabilities canEnableThumperCalling]
+ -[TUThumperCTCapabilitiesState eligibleToEnable]
+ -[TUThumperCTCapabilitiesState setEligibleToEnable:]
+ GCC_except_table152
+ GCC_except_table183
+ GCC_except_table217
+ GCC_except_table240
+ GCC_except_table245
+ GCC_except_table49
+ GCC_except_table60
+ GCC_except_table63
+ GCC_except_table72
+ _OBJC_CLASS_$_CHManager
+ _OBJC_IVAR_$_TUCallHistoryController._isPerformingRecentCallsRefresh
+ _OBJC_IVAR_$_TUCallHistoryController._recentCallsRefreshRequestedDuringFetch
+ _OBJC_IVAR_$_TUCallHistoryController._recentsDataSource
+ _OBJC_IVAR_$_TUCallServicesInterface._clientSupportsExtendedSuspensionState
+ _OBJC_IVAR_$_TUCallServicesInterface._lastOutgoingXPCMessageTime
+ _OBJC_IVAR_$_TUThumperCTCapabilitiesState._eligibleToEnable
+ __OBJC_$_CATEGORY_CHManager_$_TUCallHistoryControllerRecentsDataSourceConformance
+ __OBJC_$_PROP_LIST_CHManager_$_TUCallHistoryControllerRecentsDataSourceConformance
+ __OBJC_$_PROP_LIST_TUCallHistoryControllerRecentsDataSource
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_TUCallHistoryControllerRecentsDataSource
+ __OBJC_$_PROTOCOL_METHOD_TYPES_TUCallHistoryControllerRecentsDataSource
+ __OBJC_$_PROTOCOL_REFS_TUCallHistoryControllerRecentsDataSource
+ __OBJC_CATEGORY_PROTOCOLS_$_CHManager_$_TUCallHistoryControllerRecentsDataSourceConformance
+ __OBJC_LABEL_PROTOCOL_$_TUCallHistoryControllerRecentsDataSource
+ __OBJC_PROTOCOL_$_TUCallHistoryControllerRecentsDataSource
+ ___45+[TUCallCapabilities canEnableThumperCalling]_block_invoke
+ ___52-[TUCallHistoryController requestRecentCallsRefresh]_block_invoke
+ ___62-[TUCallCenter registerClientSupportsExtendedSuspensionState:]_block_invoke
+ _clock_gettime_nsec_np
- -[TUCallHistoryController initWithCoalescingStrategy:options:dataSource:shouldUpdateMetadataCache:]
- -[TUCallServicesInterface pickRouteWithUniqueIdentifier:shouldWaitUntilAvailable:forRouteController:]
- GCC_except_table149
- GCC_except_table159
- GCC_except_table215
- GCC_except_table237
- GCC_except_table242
- GCC_except_table41
- GCC_except_table65
- GCC_except_table70
CStrings:
+ "Asked to pick route with unique identifier: %@ (routeSelectionProvenance: %ld)"
+ "Asked to pick route: %@ (routeSelectionProvenance: %ld)"
+ "Client doesn't support extended suspension state - we should tear down the XPC connection"
+ "Daemon launch time (%llu nanoseconds since uptime) is at or after last outgoing message to server (%llu nanoseconds since uptime). We should tear down the XPC connection."
+ "Daemon launch time (%llu nanoseconds since uptime) precedes last outgoing message to server (%llu nanoseconds since uptime). We should not tear down the XPC connection"
+ "Proxying pickLocalRouteWithUniqueIdentifier for %@ shouldWaitUntilAvailable: %d routeSelectionProvenance: %ld"
+ "Proxying pickPairedHostDeviceRouteWithUniqueIdentifier for %@ shouldWaitUntilAvailable: %d routeSelectionProvenance: %ld"
+ "Recent calls refresh requested while a refresh is already in progress; queueing another refresh"
+ "Starting recent calls refresh"
+ "TUCallCenter registerClientSupportsExtendedSuspensionState: %@"
+ "Thumper capabilities changed from (supported=%d overCellularData=%d enabled=%d provisioningStatus=%d, associated=%d, supportsDefaultPairedDevice=%d canEnable=%d) to (supported=%d overCellularData=%d enabled=%d provisioningStatus=%d, associated=%d, supportsDefaultPairedDevice=%d canEnable=%d)"
+ "Updating clientSupportsExtendedSuspensionState to %d"
+ "[WARN] Bad status (%u) reading daemon launch time; we should tear down the XPC connection"
- "Asked to pick route with unique identifier: %@"
- "Asked to pick route: %@"
- "Proxying pickLocalRouteWithUniqueIdentifier for %@ shouldWaitUntilAvailable: %d"
- "Proxying pickPairedHostDeviceRouteWithUniqueIdentifier for %@ shouldWaitUntilAvailable: %d"
- "Thumper capabilities changed from (supported=%d overCellularData=%d enabled=%d provisioningStatus=%d, associated=%d, supportsDefaultPairedDevice=%d) to (supported=%d overCellularData=%d enabled=%d provisioningStatus=%d, associated=%d, supportsDefaultPairedDevice=%d)"
```
