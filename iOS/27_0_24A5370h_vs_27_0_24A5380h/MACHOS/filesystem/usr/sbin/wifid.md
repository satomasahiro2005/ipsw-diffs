## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c1760` | `0x1c1f4c` | **`+0x7ec`** |
| `__TEXT.__cstring` | `0x7518d` | `0x75423` | **`+0x296`** |
| `__DATA_CONST.__cfstring` | `0x1c520` | `0x1c6a0` | **`+0x180`** |
| `__DATA_CONST.__got` | `0x13a8` | `0x1400` | **`+0x58`** |
| `__DATA_CONST.__const` | `0x7b68` | `0x7ba8` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x14e20` | `0x14e40` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1b130` | `0x1b14f` | **`+0x1f`** |
| `__TEXT.__unwind_info` | `0x4558` | `0x4568` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x6320` | `0x6328` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x6818` | `0x6820` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-2027.13.0.0.0
+2027.18.0.0.0

-  Functions: 8781
+  Functions: 8785

-  CStrings:  17281
+  CStrings:  17300
CStrings:
+ "%s: Detaching MIS session to prevent stale host count"
+ "%s: Trial config applied — rssiDeep=%d rssi24G=%d rssi24G_MultiAP=%d rssi5G=%d rssiBadCell=%d waitShort=%.1f waitMedium=%.1f waitLong=%.1f rssiHighRSSI=%d lqaMask=0x%02x legacyMask=0x%02x augCritLink=%d augDeepRSSI=%d carPlayExempt=%d bcnPer=%.2f txPer=%.2f drive=%.0f tdImminent=%u monitorOnly=%d gateOnIC=%d gateMultiAP24GOnIC=%d alZoneHystDb=%d alRssiCap=%d wfaWalkout=%d wfaPoor2G=%d entryBoost[autoLeave=%d poor2G=%d cheap5G=%d drive=%d rtApp=%d] waitBoost[autoLeave=%d deepRSSI=%d poor2G=%d drive=%d rtApp=%d roamFail=%d noRoam=%d]"
+ "%s: Unable to detach MIS session: %s"
+ "%s: Unable to release MIS PM Assertion error=%d"
+ "%s: Unable to stop MIS service: %s"
+ "%s: Updated edge parameters for BSSID %@ - isEdge: %d, autoLeaveRssi(learnt): %d capped: %d, SSID %@ - 2G relevant: %d"
+ "%s: rssi is 0 for known network (not scan result), bypassing RSSI-based TD evaluation"
+ "AutoInstallMegaWiFiProfile"
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "LinkDownManual"
+ "LinkDownNonManual"
+ "Superseded"
+ "Teardown"
+ "WiFiDeviceManagerDetachMISSession"
+ "WiFiManager-2027.18 Jul  1 2026 23:36:07"
+ "WiFiManager-2027.18 Jul  1 2026 23:36:58"
+ "scoreTD_allowAboveDeepOnPoor2GMultiAp"
+ "scoreTD_augmentOnLinkRec"
+ "scoreTD_autoLeaveRssiCap"
+ "scoreTD_autoLeaveZoneHysteresisDb"
+ "scoreTD_linkRecExcludeOnAutoLeavePermissive"
+ "scoreTD_wifiAssistOnPoor2G"
+ "scoreTD_wifiAssistOnWalkout"
+ "terminateRequestWithEndReason:"
- "%s: Trial config applied — rssiDeep=%d rssi24G=%d rssi24G_MultiAP=%d rssi5G=%d rssiBadCell=%d waitShort=%.1f waitMedium=%.1f waitLong=%.1f rssiHighRSSI=%d lqaMask=0x%02x legacyMask=0x%02x augCritLink=%d augDeepRSSI=%d carPlayExempt=%d bcnPer=%.2f txPer=%.2f drive=%.0f tdImminent=%u monitorOnly=%d gateOnIC=%d gateMultiAP24GOnIC=%d entryBoost[autoLeave=%d poor2G=%d cheap5G=%d drive=%d rtApp=%d] waitBoost[autoLeave=%d deepRSSI=%d poor2G=%d drive=%d rtApp=%d roamFail=%d noRoam=%d]"
- "%s: Updated edge parameters for BSSID %@ - isEdge: %d, autoLeaveRssi: %d, SSID %@ - 2G relevant: %d"
- "%s: initial IC state: feature=%s user=%s effective=%s"
- "WiFiManager-2027.13 Jun 17 2026 00:36:54"
- "WiFiManager-2027.13 Jun 17 2026 00:37:49"
```
