## wirelessinsightsd

> `/System/Library/Frameworks/WirelessInsights.framework/Support/wirelessinsightsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34a1ac` | `0x34a9c4` | **`+0x818`** |
| `__TEXT.__gcc_except_tab` | `0x2a274` | `0x2a448` | **`+0x1d4`** |
| `__TEXT.__objc_methname` | `0x187ac` | `0x1892c` | **`+0x180`** |
| `__TEXT.__objc_stubs` | `0xf980` | `0xfae0` | **`+0x160`** |
| `__TEXT.__objc_methlist` | `0x783c` | `0x78a4` | **`+0x68`** |
| `__DATA.__objc_selrefs` | `0x44d0` | `0x4528` | **`+0x58`** |
| `__DATA.__objc_const` | `0x14570` | `0x145b0` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x10448` | `0x10470` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x17388` | `0x173a8` | **`+0x20`** |
| `__TEXT.__oslogstring` | `0x2ed62` | `0x2ed42` | **`-0x20`** |
| `__DATA_CONST.__objc_arrayobj` | `0x228` | `0x240` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x6b0` | `0x6c0` | **`+0x10`** |
| `__TEXT.__auth_stubs` | `0x4ff0` | `0x5000` | **`+0x10`** |
| `__TEXT.__const` | `0x17e93` | `0x17ea3` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2810` | `0x2818` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x13e0` | `0x13e8` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0xa18` | `0xa1c` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__init_offsets`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-348.0.0.0.0
+350.1.0.0.0

-  Functions: 14414
-  Symbols:   2056
-  CStrings:  10374
+  Functions: 14426
+  Symbols:   2058
+  CStrings:  10385
Symbols:
+ _OBJC_CLASS_$_NSCharacterSet
+ _TelephonyRadiosGetProduct
CStrings:
+ "350.1"
+ "350.1~147"
+ "AppleSmartBatteryPack"
+ "BorderArea is overridden in the MicroTile = %{bool}d"
+ "CarrierOutageStatusResourceUrl"
+ "DailyWirelessUsageMetric:Cellular transmit state changed to %@"
+ "DailyWirelessUsageMetric:Failed to get baseband manager, aborting"
+ "FederatedMobility[FMTimeSeriesModel]:Superseding prediction for %@"
+ "Insight has default/unset insightId, dropping the insight"
+ "Metric submission end dict is nil"
+ "Popping insight from the queue"
+ "PowerUsageMetric:Retrieved value(s): remainingPercent %@, maxPercent %@, rawRemainingChargemAh %@, rawMaxChargemAh %@, voltagemV %@, packCurrentAccumulator %@, packCurrentAccumulatorCount %@. Error: %@"
+ "RatDataUsageMetric:PrimaryInterfaceUsage. Not submitting CA event, conditions not fulfilled"
+ "Send Queryable Metric %s"
+ "T@\"NSObject<OS_dispatch_queue>\",R,N,V_queue"
+ "T@\"NSString\",&,N,V_currentCellularTransmitState"
+ "TelephonyStateRelay:Unable to query carrier resource link with nil context"
+ "WISCOA:CARRIER OUTAGE TESTING FLOW: provided PLMN (%s-%s) does not match device network (mcc=%s mnc=%s / serving mcc=%s mnc=%s); bailing out"
+ "WISCOA:Data preferred context carrier resource link: %s"
+ "WISCOA:Making API request - attempt %d/%d"
+ "WISCOA:Unable to get carrier resource link: %s"
+ "WISCOA:Unsupported baseband chipset for non-TAC carrier, skipping outage check"
+ "_currentCellularTransmitState"
+ "agg:Timer event: posting a queryable metric trigger to the Baseband"
+ "agg:[EEE] Trigger(cid=0x%x, trid=0x%x, sid=%u) - Tried to flush trigger, but it doesn't exist!"
+ "alphanumericCharacterSet"
+ "client:Add client to timer notification"
+ "componentsSeparatedByCharactersInSet:"
+ "config:No config specified -> load the default"
+ "conn:CoreAnalytics shim: Filesystem error on metadata directory! Looking for component 0x%x"
+ "context:getCarrierBundleValue:error:"
+ "currentCellularTransmitState"
+ "getCarrierOutageResourceLink:error:"
+ "getCellularTransmitState:"
+ "hasPrefix:"
+ "https://"
+ "invertedSet"
+ "isCellularTransmitStateConnected:"
+ "setCurrentCellularTransmitState:"
+ "trig:Unable to find queryable metric callback for metric 0x%x"
+ "updateDurationFieldFor:isNowActive:atTimestamp:"
+ "v32@?0@\"NSString\"8@\"DurationTracker\"16^B24"
- "348"
- "348~11"
- "AT&T"
- "BorderArea is overriden in the MicroTile = %{bool}d"
- "FederatedMobility[FMTimeSeriesModel]:Superseeding prediction for %@"
- "Metric submision end dict is nil"
- "Popping insight %u from the queue"
- "PowerUsageMetric:Retrieved value(s): remainingPercent %@, maxPercent %@, rawRemainingChargemAh %@, rawMaxChargemAh %@, voltagemV %@, packCurrentAccumulator %@, packCurrentAccumulatorCount %@"
- "RatDataUsageMetric:PrimaryInterfaceUsage. Not submitting CA event, conditions not fullfilled"
- "Send Queriable Metric %s"
- "Succeded"
- "WISCOA:Device no longer in OOS, canceling outage refetch timer"
- "WISCOA:Failed to create outage refetch timer"
- "WISCOA:Making API request - attempt %d of %d"
- "WISCOA:Refetch timer fired - checking current outage status"
- "WISCOA:Refetching confirmed outage status from carrier API"
- "WISCOA:Refetching potential outage status from crowd-sourced API"
- "WISCOA:Scheduling confirmed outage refetch for every %d minutes (configured value)"
- "WISCOA:Scheduling confirmed outage refetch for every %d minutes (default value)"
- "WISCOA:Scheduling potential outage refetch for every %d minutes"
- "WISCOA:carrierConfig not available. Scheduling confirmed outage refetch for every %d minutes (default value)"
- "agg:Timer event: posting a queriable metric trigger to the Baseband"
- "agg:[EEE] Trigger(cid=0x%x, trid=0x%x, sid=%u) - Tried to flush trigger, but it doesnt exist!"
- "apiMaxWaitDuringRetryInSecs"
- "carrierResourceLink"
- "client:Add client to timer notificaiton"
- "config:No config specifed -> load the default"
- "conn:CoreAnalytics shim: Filesytem error on metadata directory! Looking for component 0x%x"
- "https://www.att.com/outages/"
- "refetchTimerInMins"
- "trig:Unable to find queriable metric callback for metric 0x%x"
```
