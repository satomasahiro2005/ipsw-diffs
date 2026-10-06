## WiFiKitUI

> `/System/Library/PrivateFrameworks/WiFiKitUI.framework/WiFiKitUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x94518` | `0x94578` | **`+0x60`** |
| `__AUTH_CONST.__auth_got` | `0xd40` | `0xd48` | **`+0x8`** |

### Other Changes

```diff

-1205.55.0.0.0
+1205.59.4.1.0

-  Symbols:   3975
+  Symbols:   3976
Symbols:
+ _swift_retain_x23
Functions:
~ _WFErrorLogCurrentCallStackThread : 464 -> 460
~ ___101-[WFAirportViewController _updateCellsWithNewData:oldData:inSection:insertSection:datasourceSection:]_block_invoke_4 : 2744 -> 2740
~ ___50-[WFAirportViewController updateViewsForNetworks:]_block_invoke : 2500 -> 2488
~ -[WFAirportViewController titleForHeaderInSection:] : 960 -> 956
~ -[WFAirportViewController tableView:didSelectRowAtIndexPath:] : 4080 -> 4076
~ -[WFAirportViewController _dumpSections] : 436 -> 432
~ -[NSString(WiFiKitUI) formattedWiFiAddress] : 668 -> 664
~ -[WFHotspotDetailsView intrinsicContentSize] : 348 -> 344
~ -[WFOtherNetworkViewController _availableProfileModeTitles] : 332 -> 328
~ -[WFOtherNetworkViewController _availableSecurityTitles] : 332 -> 328
~ -[NSArray(WiFiKitUI) stringFromContentsOfArrayWithDelimiter:] : 392 -> 400
~ -[WFNANPublishTableViewController serviceSpecificInfoFromString] : 408 -> 412
~ ___67-[WFBuddyViewController _updateCellsWithNewData:oldData:inSection:]_block_invoke.130 -> ___67-[WFBuddyViewController _updateCellsWithNewData:oldData:inSection:]_block_invoke.145 : 636 -> 632
~ -[WFBuddyViewController _debugSectionStringFromSections:] : 404 -> 400
~ sub_2af4df3e8 -> sub_2b4c793bc : 1308 -> 1304
~ sub_2af4df904 -> sub_2b4c798d4 : 2836 -> 2840
~ sub_2af4ea4c8 -> sub_2b4c8449c : 448 -> 464
~ sub_2af4ea688 -> sub_2b4c8466c : 448 -> 464
~ sub_2af4eb944 -> sub_2b4c85938 : 5296 -> 5232
~ sub_2af4edff4 -> sub_2b4c87fa8 : 3196 -> 3292
~ sub_2af4ef0a8 -> sub_2b4c890bc : 2016 -> 2028
~ sub_2af4f28ec -> sub_2b4c8c90c : 1428 -> 1432
~ sub_2af4f2e84 -> sub_2b4c8cea8 : 324 -> 320
~ sub_2af4f3364 -> sub_2b4c8d384 : 1852 -> 1864
~ sub_2af4f49f0 -> sub_2b4c8ea1c : 2252 -> 2200
~ sub_2af4f61e4 -> sub_2b4c901dc : 280 -> 276
~ sub_2af4f7180 -> sub_2b4c91174 : 256 -> 264
~ sub_2af4f7280 -> sub_2b4c9127c : 652 -> 672
~ sub_2af4f750c -> sub_2b4c9151c : 972 -> 1048
~ sub_2af4f85c0 -> sub_2b4c9261c : 692 -> 684
~ sub_2af4f8a24 -> sub_2b4c92a78 : 388 -> 384
~ sub_2af4f8ba8 -> sub_2b4c92bf8 : 376 -> 372
~ sub_2af4f9170 -> sub_2b4c931bc : 172 -> 184
~ sub_2af4f92d8 -> sub_2b4c93330 : 272 -> 276
~ sub_2af50c270 -> sub_2b4ca62cc : 1440 -> 1428
~ sub_2af50d634 -> sub_2b4ca7684 : 1364 -> 1376
~ sub_2af514928 -> sub_2b4cae984 : 124 -> 128
```
