## CoreWiFi

> `/System/Library/PrivateFrameworks/CoreWiFi.framework/CoreWiFi`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1f85b8` | `0x1fd2c0` | **`+0x4d08`** |
| `__AUTH_CONST.__cfstring` | `0x1c800` | `0x1cf20` | **`+0x720`** |
| `__TEXT.__oslogstring` | `0x20a21` | `0x20f97` | **`+0x576`** |
| `__TEXT.__cstring` | `0x2507d` | `0x25544` | **`+0x4c7`** |
| `__AUTH_CONST.__objc_const` | `0x180a8` | `0x18258` | **`+0x1b0`** |
| `__TEXT.__objc_methlist` | `0x124bc` | `0x1260c` | **`+0x150`** |
| `__DATA_CONST.__const` | `0x5ba8` | `0x5ca8` | **`+0x100`** |
| `__DATA_CONST.__objc_selrefs` | `0x9228` | `0x9318` | **`+0xf0`** |
| `__TEXT.__gcc_except_tab` | `0x7448` | `0x752c` | **`+0xe4`** |
| `__TEXT.__unwind_info` | `0x6c90` | `0x6d60` | **`+0xd0`** |
| `__AUTH_CONST.__const` | `0x5058` | `0x50b8` | **`+0x60`** |
| `__DATA.__objc_ivar` | `0x14d8` | `0x14fc` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1060` | `0x1078` | **`+0x18`** |
| `__AUTH_CONST.__objc_intobj` | `0x3d80` | `0x3d98` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x2e0` | `0x2f0` | **`+0x10`** |
| `__TEXT.__const` | `0x7cb0` | `0x7cc0` | **`+0x10`** |

### Other Changes

```diff

-1030.65.0.0.0
+1030.70.0.0.0

-  Functions: 9388
-  Symbols:   1178
-  CStrings:  6265
+  Functions: 9431
+  Symbols:   1184
+  CStrings:  6338
Symbols:
+ _CWFDictionaryFromChannelsInfo
+ _CWFIsAutoJoinAllowDeferredCandidatesTrigger
+ _CWFKnownNetworksWithMatchingLAN
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _strnlen
CStrings:
+ "-[CWFNetworkOfInterestManager activate]_block_invoke"
+ "-[CWFNetworkProfile __lastJoinedOnAnyDeviceOrStillConnected:]"
+ "-[CWFXPCRequestProxy __durationForAdaptiveInterfaceRankInMilliseconds]"
+ "0x%04x"
+ "0x%08x"
+ "11axMirror"
+ "Ask To Join"
+ "Automatic"
+ "B24@?0@\"CWFChannel\"8^B16"
+ "CWFSendWirelessAlertAnalytics"
+ "Never"
+ "Notify"
+ "Off"
+ "On"
+ "[corewifi] %s: Failed to send %s CA event, nil arg"
+ "[corewifi] %{public}s (%{public}s:%u) CWFGetBootTime() previously returned nil, but now returned a non-nil value; will assume still-connected if joined since boot"
+ "[corewifi] %{public}s (%{public}s:%u) CWFGetBootTime() returned nil; will only assume still-connected if joined within the last %d hours"
+ "[corewifi] @[%llu.%06llu] %{public}s (%{public}s:%u) SCNetworkConfiguration: primary interface changed (%{public}@ -> %{public}@)"
+ "[corewifi] @[%llu.%06llu] %{public}s (%{public}s:%u) SCNetworkConfiguration: suppressing CWFEventTypeIPv4Changed, primary interface unchanged (%{public}@)"
+ "[corewifi] AUTO-JOIN: Adding channel (%{public}@) for join candidate '%{public}@' discovered using scan cache (cacheAge=%lums, acceptableCacheAge=%llums, autoJoinDuration=%llums)"
+ "[corewifi] AUTO-JOIN: Allowing recently-joined deferred candidates during non-deferred phase (trigger=%lu (%{public}@), nonDeferred=%lu, deferred=%lu)"
+ "[corewifi] AUTO-JOIN: CarPlay preferred channel changed from %{public}@ to %{public}@"
+ "[corewifi] AUTO-JOIN: Derived pre-association scan channel list for '%{public}@' (nearby=%{public}s, addedToSSIDList=%{public}s, locationChannels=%{public}@, recentChannels=%{public}@, maxBSSChannelAge=%lu, minBSSLocationAccuracy=%f, maxBSSLocationDistance=%f, maxBSSChannelCount=%lu, location=%{public}@, hasCompletedSinceFirstUnlock=%d, useAcceptableCacheAge=%d)"
+ "[corewifi] Link Quality Assessment (calculated from LQM) - RSSI: %ld dBm, CCA: %lu, hasStats: %d, txRate: %f Mbps, rxRate: %f Mbps, txPer: %lu, txFrames: %lu, Score (0-4, UnKnown -> Good): %d, subScores (ch:%d, txloss:%d), Estimated Throughput: %lu Mbps, UpdatedAt: %@, Band: %s, ThroughputMethod: %s."
+ "[corewifi] [wifi-network-sharing] Adding automatically-shareable colocated network for clientID (clientID=%{public}@, knownNetwork=%{public}@)"
+ "[corewifi] [wifi-network-sharing] Performing next ask-to-share scan immediately"
+ "[corewifi] [wifi-network-sharing] Scheduling next ask-to-share scan (fromNow=%ds)"
+ "[corewifi] [wifi-network-sharing] Unscheduling next ask-to-share scan"
+ "[corewifi] [wifi-network-sharing] Using authorization client %{public}@ for ask-to-share scan"
+ "_adaptiveInterfaceRankDuration"
+ "_durationForAdaptiveInterfaceRankInMilliseconds"
+ "adaptiveInterfaceRankDelay"
+ "adaptiveInterfaceRankDuration"
+ "alert_action"
+ "alert_available_actions"
+ "alert_id"
+ "alert_id_domain"
+ "ask_to_join_mode"
+ "auto_hotspot_mode"
+ "bandwidth"
+ "bundle"
+ "cancel"
+ "channel_bitmap"
+ "channel_num"
+ "channel_spec"
+ "com.apple.wireless.alertsAndActions"
+ "compatibility_mode"
+ "corewifi.corewifi"
+ "dismiss"
+ "dont_share"
+ "index"
+ "indoor_restricted"
+ "is_lpi_allowed"
+ "is_p2p_vlp_allowed"
+ "is_vlp_allowed"
+ "join,dismiss"
+ "lastJoinErrorCategoryDescription"
+ "linkUpDuration"
+ "linkUpLatency"
+ "matchingKnownNetworkProfile.lastJoinedOrStillConnectedOnAnyDeviceAt"
+ "max_lpi_tx_power_160mhz"
+ "max_lpi_tx_power_20mhz"
+ "max_vlp_tx_power_160mhz"
+ "max_vlp_tx_power_20mhz"
+ "nearby_captive_assist"
+ "num_channels"
+ "os_specific_attributes"
+ "passive"
+ "per_chan_info"
+ "radar_dfs"
+ "share"
+ "share,dont_share,cancel"
+ "share_this_network"
+ "share_this_network,dismiss"
+ "share_wifi_with_accessory"
+ "sync_mode"
+ "system-dismiss"
+ "unstable_internet_connection"
+ "uuid=%@, intf=%@, ssid='%@' (%@), error=%ld, eap=[sup=%d mode=%d state=%d client=%d], start=%@, assoc=%@ (%lums), auth=%@ (%lums), linkup=%@ (%lums), end=%@ (%lums), ipv4=%@ (%lums), ipv4Primary=%@ (%lums), ipv6=%@ (%lums), ipv6Primary=%@ (%lums), auto=%s, pmAssertion=%lums, adaptiveIntfRank=%lums"
+ "v16@?0Q8"
+ "version"
+ "wifi_network_sharing"
- "-[CWFNetworkOfInterestManager activate]"
- "[corewifi] AUTO-JOIN: Adding channel (%{public}@) for join candidate '%{public}@' discovered using scan cache (cacheAge=%lums, acceptableCacheAge=%llums)"
- "[corewifi] AUTO-JOIN: Derived pre-association scan channel list for '%{public}@' (nearby=%{public}s, addedToSSIDList=%{public}s, locationChannels=%{public}@, recentChannels=%{public}@, maxBSSChannelAge=%lu, minBSSLocationAccuracy=%f, maxBSSLocationDistance=%f, maxBSSChannelCount=%lu, location=%{public}@, hasCompletedSinceFirstUnlock=%d)"
- "[corewifi] [wifi-network-sharing] Performing next ask-to-share scan immediately (clientID=%{public}@)"
- "[corewifi] [wifi-network-sharing] Scheduling next ask-to-share scan (clientID=%{public}@, fromNow=%ds)"
- "[corewifi] [wifi-network-sharing] Unscheduling next ask-to-share scan (clientID=%{public}@)"
- "lastJoinErrorCategoryDesc"
- "matchingKnownNetworkProfile.lastJoinedOnAnyDeviceAt"
- "uuid=%@, intf=%@, ssid='%@' (%@), error=%ld, eap=[sup=%d mode=%d state=%d client=%d], start=%@, assoc=%@ (%lums), auth=%@ (%lums), linkup=%@ (%lums), end=%@ (%lums), ipv4=%@ (%lums), ipv4Primary=%@ (%lums), ipv6=%@ (%lums), ipv6Primary=%@ (%lums), auto=%s, durationForJoinPMAssertion=%f"
```
