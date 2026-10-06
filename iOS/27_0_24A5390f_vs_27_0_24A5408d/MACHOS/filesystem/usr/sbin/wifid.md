## wifid

> `/usr/sbin/wifid`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1c3224` | `0x1c38bc` | **`+0x698`** |
| `__TEXT.__cstring` | `0x758b2` | `0x75aae` | **`+0x1fc`** |
| `__TEXT.__ustring` | `0x4c2` | `0x63e` | **`+0x17c`** |
| `__DATA_CONST.__cfstring` | `0x1c7a0` | `0x1c8e0` | **`+0x140`** |
| `__TEXT.__objc_methname` | `0x1b37f` | `0x1b3bb` | **`+0x3c`** |
| `__DATA_CONST.__objc_arraydata` | `0x718` | `0x748` | **`+0x30`** |
| `__DATA_CONST.__objc_arrayobj` | `0x258` | `0x288` | **`+0x30`** |
| `__DATA_CONST.__const` | `0x7c00` | `0x7c28` | **`+0x28`** |
| `__TEXT.__objc_stubs` | `0x14fa0` | `0x14fc0` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x29a8` | `0x29b8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x68a0` | `0x68b0` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x6390` | `0x6398` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x45a0` | `0x45a8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-2027.24.0.0.0
+2027.32.0.0.0

-  Functions: 8809
+  Functions: 8810

-  CStrings:  17347
+  CStrings:  17360
CStrings:
+ "%s: %@ already in a seamless SSID list with the current network; already provisioned, skipping"
+ "%s: candidate %@ is not 5GHz (band=%d); skipping transient join (colocated provisioning is 5GHz-only)"
+ "%s: skipping %@ — colocated provisioning is 5GHz-only (chanFlags=0x%x)"
+ "5GHz Network Required"
+ "Allow 5GHz Connection?"
+ "ColocatedJoinContext"
+ "Home Theater requires a 5GHz Wi-Fi connection. Connect to “%@”, or use TV speakers."
+ "Preferences SpringBoard Carousel WiFiPickerExtens Setup budd sharingd demod BundledIntentHandler SiriViewService assistantd assistant_service Siri SettingsIntentExtension NanoSettings PineBoard TVSettings SoundBoard RealityControlCenter MuseBuddyApp mobilewifitool WirelessStress coreautomationd hermeswifid remotedevicekitwifid wifiutil NanoWiFiViewService ATKWiFiFramework WiFiViewService hQT XCTestInternalAngel HPSetup AirPlaySenderUIApp TVSetup deviceaccessd AccessorySetupUI Setup RealityCoverSheet WiFiProxUI"
+ "Some Apple TV features like AirPlay require a 5GHz connection. Allow Apple TV to join “%@” when required?"
+ "WIFI_COLOCATED_5G_ALLOW_BODY"
+ "WIFI_COLOCATED_5G_ALLOW_TITLE"
+ "WIFI_HOMETHEATER_5G_REQUIRED_BODY"
+ "WIFI_HOMETHEATER_5G_REQUIRED_BODY_CH"
+ "WIFI_HOMETHEATER_5G_REQUIRED_TITLE"
+ "WiFiManager-2027.32 Aug  4 2026 03:01:43"
+ "WiFiManager-2027.32 Aug  4 2026 03:02:33"
+ "corresponding5GhzSsidForScannedNetworkViaSaltedBssid:"
+ "eventsForEntityNames:withError:"
+ "remotedevicekitwifid"
- "MockA2DPActivity"
- "Preferences SpringBoard Carousel WiFiPickerExtens Setup budd sharingd demod BundledIntentHandler SiriViewService assistantd assistant_service Siri SettingsIntentExtension NanoSettings PineBoard TVSettings SoundBoard RealityControlCenter MuseBuddyApp mobilewifitool WirelessStress coreautomationd hrmwifid hermeswifid wifiutil NanoWiFiViewService ATKWiFiFramework WiFiViewService hQT XCTestInternalAngel HPSetup AirPlaySenderUIApp TVSetup deviceaccessd AccessorySetupUI Setup RealityCoverSheet WiFiProxUI"
- "WiFiManager-2027.24 Jul 11 2026 04:27:09"
- "WiFiManager-2027.24 Jul 11 2026 04:27:52"
- "availableEventsWithError:"
- "hrmwifid"
```
