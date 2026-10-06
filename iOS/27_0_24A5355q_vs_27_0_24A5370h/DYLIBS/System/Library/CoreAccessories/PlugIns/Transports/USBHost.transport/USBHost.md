## USBHost

> `/System/Library/CoreAccessories/PlugIns/Transports/USBHost.transport/USBHost`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x188d0` | `0x18870` | **`-0x60`** |
| `__AUTH_CONST.__cfstring` | `0x17c0` | `0x17e0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x19a3` | `0x19bb` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x9a8` | `0x9b8` | **`+0x10`** |

### Other Changes

```diff

-1176.0.26.502.1
+1196.0.0.502.1

-  Symbols:   1231
-  CStrings:  496
+  Symbols:   1233
+  CStrings:  497
Symbols:
+ _ACCUserDefaultsKey_PretendWirelessCTAMatch
+ _kCFACCUserDefaultsKey_PretendWirelessCTAMatch
Functions:
~ -[AccessoryUSBBillboardDeviceManager stopDetectUSBBillboardDeviceAll] : 332 -> 328
~ ___46-[AccessoryTransportPluginUSBHost startPlugin]_block_invoke : 1748 -> 1740
~ ___50-[AccessoryTransportPluginUSBHost serviceRemoved:]_block_invoke : 444 -> 440
~ ___50-[AccessoryTransportPluginUSBHost serviceRemoved:]_block_invoke_3 : 324 -> 320
~ -[AccessoryTransportPluginUSBHost unlockUSBHostInterfacesForConnectionUUID:] : 1480 -> 1476
~ ___56-[AccessoryTransportPluginUSBHost VIDPIDServiceRemoved:]_block_invoke : 404 -> 400
~ ___init_logging_signpost_modules_block_invoke : 608 -> 588
~ -[ACCUserNotificationManager dismissNotificationWithIdentifier:] : 540 -> 532
~ -[ACCUserNotificationManager dismissNotificationsWithGroupIdentifier:] : 540 -> 532
~ -[ACCUserNotificationManager dismissAllNotifications] : 320 -> 316
~ -[ACCUserNotificationManager userNotificationWithUUID:] : 388 -> 384
~ ___init_logging_modules_block_invoke : 608 -> 588
~ -[AccessoryUSBCDCInterface writeData:] : 816 -> 808
~ -[AccessoryUSBCDCInterface _handleReadDataCallback:revent:t_look:] : 608 -> 612
CStrings:
+ "PretendWirelessCTAMatch"
```
