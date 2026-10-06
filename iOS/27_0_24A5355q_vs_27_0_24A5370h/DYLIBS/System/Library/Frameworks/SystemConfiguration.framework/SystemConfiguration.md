## SystemConfiguration

> `/System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7969c` | `0x79718` | **`+0x7c`** |
| `__TEXT.__const` | `0x2d0` | `0x2c0` | **`-0x10`** |

### Other Changes

```diff

-1434.0.0.502.1
+1438.0.0.0.0
Functions:
~ _SCNetworkReachabilityCreateWithAddress : 476 -> 472
~ __SC_sockaddr_to_string : 356 -> 360
~ _copyIORegistryProperties : 208 -> 212
~ __SC_CFBundleGet : 820 -> 812
~ ____SC_hw_model_block_invoke : 460 -> 472
~ _SCNetworkSetCopyServices : 1436 -> 1420
~ __SCCopyDescription : 1844 -> 1848
~ __SCSerializeMultiple : 588 -> 580
~ __SCUnserializeMultiple : 572 -> 564
~ __SCNetworkInterfaceCreateWithBSDName : 1164 -> 1156
~ _SCCopyLastError : 364 -> 372
~ _SCErrorString : 280 -> 288
~ __SC_logMachPortStatus : 784 -> 768
~ __SC_copyBacktrace : 504 -> 508
~ ___SCNetworkConfigurationCleanHiddenInterfaces : 4812 -> 4816
~ ___SCNetworkConnectionIPv6AddressMatchesRoutes : 504 -> 496
~ ___SCNetworkInterfaceCreateCapabilities : 376 -> 384
~ _SCNetworkInterfaceCopyCapability : 464 -> 492
~ _SCNetworkInterfaceSetCapability : 524 -> 544
~ ___SCNetworkInterfaceCreateMediaOptions : 840 -> 872
~ _SCNetworkInterfaceCopyMediaOptions : 556 -> 544
~ ___createMediaDictionary : 640 -> 648
~ __SCNetworkInterfaceIsPhysicalEthernet : 380 -> 388
~ ___SCNetworkInterfaceGetDefaultConfigurationType : 184 -> 204
~ _findConfiguration : 144 -> 148
~ ___SCNetworkInterfaceIsValidExtendedConfigurationType : 380 -> 396
~ ___SCNetworkInterfaceCopyInterfaceEntity : 484 -> 504
~ _SCNetworkInterfaceGetSupportedInterfaceTypes : 412 -> 432
~ _SCNetworkInterfaceGetSupportedProtocolTypes : 364 -> 384
~ _copyConfigurationPaths : 316 -> 340
~ _extendedConfigurationTypes : 536 -> 548
~ _get_number_value : 372 -> 392
~ _set_number_value : 476 -> 488
~ ___SCNetworkInterfaceCopyFormattingDescription : 1964 -> 1960
~ _SCNetworkServiceCopyAll : 1348 -> 1316
~ __copyInterfaceEntityTypes : 340 -> 348
~ _SCNetworkServiceCopyProtocols : 724 -> 716
~ _SCNetworkSetCopyAll : 808 -> 796
~ __SCNetworkMigrationAreConfigurationsIdentical : 4088 -> 4032
~ _SCNetworkSignatureCopyActiveIdentifiers : 1316 -> 1312
~ _SCNetworkSignatureCopyIdentifierForConnectedSocket : 1128 -> 1124
~ __SCBridgeInterfaceCopyActive : 1220 -> 1216
~ _store_set_notification_keys : 564 -> 572
```
