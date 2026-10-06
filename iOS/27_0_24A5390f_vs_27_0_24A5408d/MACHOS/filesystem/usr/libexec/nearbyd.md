## nearbyd

> `/usr/libexec/nearbyd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x54fc54` | `0x554e78` | **`+0x5224`** |
| `__TEXT.__objc_methtype` | `0x2229d` | `0x22c2d` | **`+0x990`** |
| `__TEXT.__oslogstring` | `0x629c5` | `0x632a5` | **`+0x8e0`** |
| `__TEXT.__gcc_except_tab` | `0x54774` | `0x54f8c` | **`+0x818`** |
| `__TEXT.__objc_methname` | `0x230e5` | `0x23545` | **`+0x460`** |
| `__TEXT.__objc_stubs` | `0x16dc0` | `0x170c0` | **`+0x300`** |
| `__DATA.__objc_const` | `0x1b1b8` | `0x1b4a0` | **`+0x2e8`** |
| `__DATA_CONST.__cfstring` | `0x17240` | `0x17420` | **`+0x1e0`** |
| `__TEXT.__objc_methlist` | `0xf504` | `0xf694` | **`+0x190`** |
| `__TEXT.__cstring` | `0x3890c` | `0x38a7c` | **`+0x170`** |
| `__TEXT.__unwind_info` | `0x1cc18` | `0x1cd80` | **`+0x168`** |
| `__DATA.__objc_selrefs` | `0x6fc0` | `0x7080` | **`+0xc0`** |
| `__DATA.__objc_data` | `0x4928` | `0x4978` | **`+0x50`** |
| `__DATA.__objc_ivar` | `0x19a8` | `0x19f0` | **`+0x48`** |
| `__TEXT.__const` | `0x3fa810` | `0x3fa840` | **`+0x30`** |
| `__TEXT.__objc_classname` | `0x202e` | `0x204e` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x1f240` | `0x1f258` | **`+0x18`** |
| `__DATA_CONST.__objc_intobj` | `0x978` | `0x990` | **`+0x18`** |
| `__DATA_CONST.__objc_classlist` | `0x628` | `0x630` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x528` | `0x530` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-564.0.0.0.0
+569.0.0.0.0

-  Functions: 23388
+  Functions: 23450

-  CStrings:  19733
+  CStrings:  19828
CStrings:
+ " - Client Name: [%s], initiator_addr: [%u], start_TS: [%@], end_TS: [%@], total_duration: [%.4f s], initiator_mac_addr: [0x%02x]\n                Session Updates:  raw_measurement: [%u], vio_input_count: [%u], pdr_input_count: [%u], latest_uwb_rssi: [%ld dBm], initial_oob_rssi: [%ld dBm]"
+ "#!"
+ "#btcs,Apple peer VID: 0x%{sensitive}04X, PID: 0x%{sensitive}04X, productVersion: 0x%{sensitive}04X"
+ "#btcs,Device Information Service (0x180A) not exposed by peer"
+ "#btcs,Peer is non-Apple (vendorIDSource=%{sensitive}u, vendorID=0x%{sensitive}04X)"
+ "#btcs,PnP ID characteristic (0x2A50) not present on peer"
+ "#btcs,PnP ID payload too short: %lu bytes"
+ "#btcs,didDiscoverCharacteristicsForService error: %@"
+ "#btcs,didDiscoverServices error: %@"
+ "#btcs,didUpdateValueForCharacteristic error: %@"
+ "#btcs,processCombineMatchingIQ combinedIQ: %@"
+ "#btcs,start gathering pid/vid via PnP ID GATT read"
+ "#dltdoa-ble-oob,Discovered DL-TDOA anchor via BLE: MAC=0x%04hx, RSSI: %ld, oobPayload=%s"
+ "#dltdoa-cluster-select,Found cluster 0x%02hx: using  %s current RSSI=%ld dBm (smoothed=%ld dBm)"
+ "#dltdoa-cluster-select,Pending cluster 0x%02hx (OOB RSSI=%ld) qualifies to replace active cluster 0x%02hx (UWB RSSI=%ld, discovery OOB RSSI=%ld, measurements=%u)"
+ "#dltdoa-cluster-select,Scanned OOB result: %s. NO UWB network Id found in OOB"
+ "#dltdoa-cluster-select,Scanned OOB result: %s. uwb session id: [0x%02x], not match client's network identifier: [0x%02x]"
+ "#dltdoa-cluster-select,recordAnchorMeasurementsForCluster: 0x%02hx, latest_uwb_rssi: %ld, anchors.size(): %zu"
+ "#ni-ca,BTCS common summary submission"
+ "#ni-ca,BTCS finder event submission"
+ "#ni-ca,[%@] send analytics event %@ (BTCS):\n%@\n"
+ "#ses-btcs,Authorization error for %{public}@,error,%{public}@"
+ "#ses-btcs,Authorized - starting visit updates"
+ "#ses-btcs,BTCS peer identity: vendorIDSource=%{sensitive}u, VID=0x%{sensitive}04X, PID=0x%{sensitive}04X"
+ "#ses-btcs,Initializing CLLocationManager for visit monitoring"
+ "#ses-btcs,[_clLocationManager CB] didReportVisit but wrong manager"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] input visit place type: %s"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] no place inference found - user is in transit"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] no visit found"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] recorded visit type: HOME"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] recorded visit type: UNKNOWN"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] visit found"
+ "#ses-btcs,[_convertCLVisitToVisitPlaceType] visit has departure date - user is in transit"
+ "#ses-btcs,isAuthorizedForLocations: %s"
+ "#ses-ecosystem,updateMotionState got new motionState: %ld"
+ "#ses-loc,attempted to start tracking stronger pending cluster [0x%02hx] in the freed slot, result: %s"
+ "#ses-loc,cluster [0x%02hx] evicted in favor of stronger pending cluster [0x%02hx], invalidate succeed? :%d"
+ "180A"
+ "2A50"
+ "@\"<NIDLTDOAClusterSelectorDelegate>\""
+ "@\"NIDLTDOAClusterSelector\""
+ "@40@0:8@16@24I32B36"
+ "AppleUnknown"
+ "BTCSAccessory"
+ "BTCSAccessory1"
+ "BTCSAccessory2"
+ "ChannelSoundingParticleFilterUncertaintyHysteresis"
+ "ChannelSoundingParticleFilterUncertaintyThresh"
+ "ItemBTChannelSounding"
+ "LE uncertainty: RSSI unavailable, skipping Rayleigh model (uncertainty=0.0)"
+ "NIDLTDOAClusterSelector"
+ "NIDLTDOAClusterSelectorDelegate"
+ "Others"
+ "ReplacedByStrongerPendingCluster"
+ "_armFlushSelectionTimerIfNeeded"
+ "_btcsDisconnectionCount"
+ "_btcsLaunchedFromNI"
+ "_bypassNetworkIdentifierCheck"
+ "_cachedDeviceState"
+ "_clusterSelector"
+ "_flushSelectionTimer"
+ "_lastKnownRSSI"
+ "_lastSessionStartTimestamp"
+ "_parseBeaconData"
+ "_payloadMatchesNetworkIdentifier:"
+ "_pendingClusterRSSI"
+ "_pruneClustersNotSeenWithinSmoothingWindow"
+ "_recentRSSISamples"
+ "_seekForReplacementIfAny"
+ "_selectRSSIForCluster:"
+ "_sessionHasNoUniqueAnchors:"
+ "_stopFlushSelectionTimer"
+ "_submitBTChannelSoundingSummaryWithDuration:"
+ "_timeAtFirstRawBTCSRange"
+ "_updateSmoothedRSSIForCluster:sample:"
+ "avgRangingRate"
+ "channelSoundingManager:didDiscoverPeerVendorID:productID:vendorIDSource:"
+ "com.apple.nearbyinteraction.btchannelsounding"
+ "disconnectionEvent"
+ "endAllTrackingSessions"
+ "endTrackingSessionForCluster:"
+ "fallback band"
+ "flushSelection"
+ "incrementBTCSDisconnectionCount"
+ "initWithQueue:clusterSelector:"
+ "initWithQueue:delegate:networkIdentifier:bypassNetworkIdentifierCheck:"
+ "launchedFromNI"
+ "longValue"
+ "lookupVIDPIDForPeripheral:"
+ "notifyWifiScanUpdate"
+ "preferred band"
+ "printableActiveSessionsState"
+ "q28@0:8S16q20"
+ "recordAnchorMeasurementsForCluster:anchors:"
+ "recordDiscoveredPayload:rssi:preferredBand:"
+ "recordPDRInputForAllActiveSessions"
+ "recordVIOInputForAllActiveSessions"
+ "regulatory,settings,setInRestrictedRegion,ignoreUpdates,isUWBChannelSettingChanged,%d,isUWBPowerTableChanged,%d,isNBChannelSettingChanged,%d,isNBPowerTableChanged,%d"
+ "selectSessionToReplaceWithStrongestPendingCluster"
+ "startTrackingSessionForCluster:clientIdentifier:"
+ "updateDiscoveryMethod:"
+ "updateWithBTCSPeerVendorID:productID:"
+ "v128@0:8{SessionRecord=IIdIIIqq{set<unsigned short, std::less<unsigned short>, std::allocator<unsigned short>>={__tree<unsigned short, std::less<unsigned short>, std::allocator<unsigned short>>=^v{?={__tree_end_node<std::__tree_node_base<void *> *>=^v}}{?=Q}}}{optional<double>=(?=cd)B}{basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}16"
+ "v24@0:8S16S20"
+ "v28@0:8S16r^v20"
+ "v36@0:8@\"ChannelSoundingManager\"16S24S28C32"
+ "v36@0:8@16S24S28C32"
+ "v36@0:8r^v16q24B32"
+ "{BTCSItemFinderAlgorithmConfig=BBB{ParticleFilterConfig=BBqBBBdddddddddddddBBddddddBdddddddddddddddddddddddddddddddBBBBBdiddddiB{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}}{SyntheticApertureConfig=BBBBBdd}B}16@0:8"
+ "{PeopleFinderAlgorithmConfig=BBBBBBBdddddddd{ParticleFilterConfig=BBqBBBdddddddddddddBBddddddBdddddddddddddddddddddddddddddddBBBBBdiddddiB{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}}B{GnssReliabilityIndicatorConfig=dd}BdBBB}16@0:8"
+ "{map<unsigned short, (anonymous namespace)::ClusterRSSIInfo, std::less<unsigned short>, std::allocator<std::pair<const unsigned short, (anonymous namespace)::ClusterRSSIInfo>>>=\"__tree_\"{__tree<std::__value_type<unsigned short, (anonymous namespace)::ClusterRSSIInfo>, std::__map_value_compare<unsigned short, std::pair<const unsigned short, (anonymous namespace)::ClusterRSSIInfo>, std::less<unsigned short>>, std::allocator<std::pair<const unsigned short, (anonymous namespace)::ClusterRSSIInfo>>>=\"__begin_node_\"^v\"\"{?=\"__end_node_\"{__tree_end_node<std::__tree_node_base<void *> *>=\"__left_\"^v}}\"\"{?=\"__size_\"Q}}}"
+ "{map<unsigned short, long, std::less<unsigned short>, std::allocator<std::pair<const unsigned short, long>>>=\"__tree_\"{__tree<std::__value_type<unsigned short, long>, std::__map_value_compare<unsigned short, std::pair<const unsigned short, long>, std::less<unsigned short>>, std::allocator<std::pair<const unsigned short, long>>>=\"__begin_node_\"^v\"\"{?=\"__end_node_\"{__tree_end_node<std::__tree_node_base<void *> *>=\"__left_\"^v}}\"\"{?=\"__size_\"Q}}}"
+ "{map<unsigned short, std::deque<std::pair<double, long>>, std::less<unsigned short>, std::allocator<std::pair<const unsigned short, std::deque<std::pair<double, long>>>>>=\"__tree_\"{__tree<std::__value_type<unsigned short, std::deque<std::pair<double, long>>>, std::__map_value_compare<unsigned short, std::pair<const unsigned short, std::deque<std::pair<double, long>>>, std::less<unsigned short>>, std::allocator<std::pair<const unsigned short, std::deque<std::pair<double, long>>>>>=\"__begin_node_\"^v\"\"{?=\"__end_node_\"{__tree_end_node<std::__tree_node_base<void *> *>=\"__left_\"^v}}\"\"{?=\"__size_\"Q}}}"
+ "{optional<ClusterReplacementDecision>=(?=c{ClusterReplacementDecision=SS})B}16@0:8"
+ "{optional<SessionRecord>=(?=c{SessionRecord=IIdIIIqq{set<unsigned short, std::less<unsigned short>, std::allocator<unsigned short>>={__tree<unsigned short, std::less<unsigned short>, std::allocator<unsigned short>>=^v{?={__tree_end_node<std::__tree_node_base<void *> *>=^v}}{?=Q}}}{optional<double>=(?=cd)B}{basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}})B}20@0:8S16"
+ "{optional<nearby::algorithms::device_presence::DeviceState>=\"\"(?=\"__null_state_\"c\"__val_\"i)\"__engaged_\"B}"
+ "{vector<(anonymous namespace)::PendingWifiDiscovery, std::allocator<(anonymous namespace)::PendingWifiDiscovery>>=^{PendingWifiDiscovery}^{PendingWifiDiscovery}{?=^{PendingWifiDiscovery}}}16@0:8"
+ "{vector<SessionRecord, std::allocator<SessionRecord>>=^{SessionRecord}^{SessionRecord}{?=^{SessionRecord}}}16@0:8"
+ "\xf0\xf0r"
- " (both bands available)"
- " - Client Name: [%s], initiator_addr: [%u], start_TS: [%@], end_TS: [%@], total_duration: [%.4f s], initiator_mac_addr: [0x%02x]\n                Session Updates:  raw_measurement: [%u], vio_input_count: [%u], pdr_input_count: [%u]"
- "#dltdoa-ble-oob,Discovered DL-TDOA anchor via BLE: MAC=0x%04hx, oobPayload=%s"
- "#dltdoa-wifi-oob,Found anchor 0x%02hx: using %s RSSI=%ld dBm%s"
- "#ni-ca,NIItemFinderBTFinding"
- "#ses-loc,Scanned OOB result: %s. Mac addr: [0x%02hx], uwb session id: [0x%02x], not match client's network identifier: [0x%02lx]"
- "#ses-loc,Scanned OOB result: %s. NO UWB network Id found in OOB"
- "2.4GHz"
- "@\"<NIDLTDOAOOBScannerDelegate>\""
- "NIDLTDOAOOBScannerDelegate"
- "Other bands"
- "_notifyDelegateWithPayloads:anchorBandRSSI:cacheCount:"
- "_processBeaconData"
- "_selectPreferredRSSI:"
- "_sortAnchorsByRSSI:"
- "initWithQueue:delegate:"
- "regulatory,settings,setInRestrictedRegion,ignoreUpdates,isChannelSettingChanged,%d,isPowerTableChanged,%d"
- "v40@0:8r^v16r^v24Q32"
- "v88@0:8{SessionRecord=IIdIII{optional<double>=(?=cd)B}{basic_string<char, std::char_traits<char>, std::allocator<char>>={?=(__rep={__short=[23c]b7b1}{__long=*Qb63b1})}}}16"
- "{BTCSItemFinderAlgorithmConfig=BBB{ParticleFilterConfig=BBqBBBdddddddddddddBBddddddBdddddddddddddddddddddddddddddddBBBBdiddddiB{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}}{SyntheticApertureConfig=BBBBBdd}B}16@0:8"
- "{PeopleFinderAlgorithmConfig=BBBBBBBdddddddd{ParticleFilterConfig=BBqBBBdddddddddddddBBddddddBdddddddddddddddddddddddddddddddBBBBdiddddiB{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}{vector<nearby::algorithms::common::TLocationScaleParamsWithRange, std::allocator<nearby::algorithms::common::TLocationScaleParamsWithRange>>=^{TLocationScaleParamsWithRange}^{TLocationScaleParamsWithRange}{?=^{TLocationScaleParamsWithRange}}}}B{GnssReliabilityIndicatorConfig=dd}BdBBB}16@0:8"
- "{map<unsigned short, BandRSSIInfo, std::less<unsigned short>, std::allocator<std::pair<const unsigned short, BandRSSIInfo>>>={__tree<std::__value_type<unsigned short, BandRSSIInfo>, std::__map_value_compare<unsigned short, std::pair<const unsigned short, BandRSSIInfo>, std::less<unsigned short>>, std::allocator<std::pair<const unsigned short, BandRSSIInfo>>>=^v{?={__tree_end_node<std::__tree_node_base<void *> *>=^v}}{?=Q}}}16@0:8"
- "{vector<std::pair<unsigned short, long>, std::allocator<std::pair<unsigned short, long>>>=^v^v{?=^v}}24@0:8r^v16"
- "\xf0\xf0b"
```
